# VideoOS lua app
[VideoOS open](http://videojj.com/videoos-open/)是由极链科技推出的视频小程序

## 什么是视频小程序
“小程序”这个是由微信最早提出的，国内的其他互联网巨头也相继推出了自己的小程序。小程序是一种新的开放能力，开发者可以快速地开发一个小程序，它可以被便捷地获取和传播，同时具有出色的用户体验。
“视频小程序”也继承了上述小程序的优势，但是不局限于特定的APP，它运行在客户自己的APP视频播放器之上。目前我们已经适配了市面上占有率较高的几款播放器：阿里云播放器、七牛云播放器、ijkplayer等。
视频小程序是基于[OS Lua](OS_Lua.md)方案，一个简单的小程序，由一个几百行的lua脚本加一个几十行的 json 配置文件组成。

## 有哪些特性
### 开源
VideoOS open 选择 [GPL v3](LICENSE) 作为开源协议，限制较少，用户可以进行本地化部署用于商业用途，并根据自身业务做二次开发。

### 轻量级
VideoOS open 的动态化解决方案基于阿里开源的 LuaViewSDK。Lua 是一个高效灵活的语言，它可以非常方便地绑定各类底层库，在 iOS 上单个 Lua 虚拟机仅占用200K到300K。集成 VideoOS open 的移动端 SDK 后，APP 包体增加控制在2.5M以内。

### 热更新
开发者完成 Lua 脚本开发后，只需要在控制台上传，并进行投放，新应用即可触达用户。开发，测试，上线完整的流程可以缩短到1周时间。

## 官方小程序
官方目前已经开发了气泡对话、卡牌收集、中插广告、投票、云图等小程序，用户也可以对这些应用的 Lua 脚本稍作修改，针对各自的行业做定制化开发。
官方小程序代码已经在github开源：[VideoOS-lua-app](https://github.com/VideoOS/VideoOS-lua-app)
