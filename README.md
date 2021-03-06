# m3u8 to mp4

## 简介

该软件包的功能是将本地 m3u8 文件转换为 mp4 文件，以便进行任意形式的存储。

### 开发原因

我在手机端经常使用 UC 浏览器观看视频，并且频繁使用 UC 的视频播放器进行缓存。

之后我想将这些文件存储到其他的地方时，发现了 m3u8 的文件，所以才会有这一个包的出现。

## 环境要求

您需要安装FFmpeg，并且已经为其配置好了环境变量。

还需要使用npm全局安装了ts-node

## 使用方法

1. 首先，您应该将 UC 浏览器缓存的 m3u8 文件正确地在电脑硬盘中进行存储。
2. 在配置文件 `./config/index.js` 中填入正确的信息。
3. 然后通过 node 启动当前程序包。

### 启动方法

可以通过内置脚本启动

```shell
npm start
```

也可以通过 node 直接启动入口文件

```shell
node ./src/index.js
```

## 特别注意

由于 m3u8 文件关联着大量的其他文件，您必须确保以下几点才能够正常进行转换。

- 请确保已将所有文件放在正确的、易读的全英文（不包括特殊字符）路径中。
- 输出路径同样按照此要求进行处理。

## 新特性

## 开发计划

以下计划存在较大不确定性，如有特殊要求，可以提交issue。

1. 使用TS重写项目（正在进行中）。
2. 提供更加合理的配置项
3. 提供国际化的命令行使用方式。
4. 搭建一个文档网站。
5. 增加一个专门用来处理转换功能的桌面程序。

## 赞赏

如果您这个包对您有帮助，且有意愿的话，您可以通过以下方式对我进行支持，非常感谢。

如果您能够进行大额打赏的话，我将会成为您的JS、NodeJS开发顾问。

您的任何提问我都会在24小时内进行回复，您可通过邮箱 `marxzhou@aliyun.com` 联系我获取我最新的联系方式。

<div style='position:relative;'>
<img src="./assets/ali.jpg" alt="支付宝" style="zoom:35%;display:inline;float: left" />
<img src="./assets/wechat.png" alt="微信" style="zoom:26%;display:inline;flex: 1;float:left;" />
<div style='clear: both' />
</div>
