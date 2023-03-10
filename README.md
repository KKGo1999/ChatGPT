# ChatGPT保姆教程
[![](https://shields.io/github/stars/kkgo1999/Stable-diffusion-person?style=social)](https://github.com/KKGo1999) &nbsp;
[![](https://shields.io/twitter/follow/kkgo1999?label=Follow)](https://twitter.com/kkgo1999) &nbsp;
[![](https://img.shields.io/badge/Telegram--green?style=social&logo=telegram)](https://t.me/+kS-jBrht-ZRiZTU1) &nbsp;
[![](https://img.shields.io/badge/WeChat%20%E5%BE%AE%E4%BF%A1--green?style=social&logo=wechat)](https://www.kkgo1999.top/img/kkgo1999.wechat.jpg) &nbsp;
[![](https://img.shields.io/badge/Youtube--green?style=social&logo=youtube)](https://youtube.com/@KKGo1999) &nbsp;
[![](https://img.shields.io/badge/Bilibili%20B%E7%AB%99--green?style=social&logo=bilibili)](https://space.bilibili.com/406715814) &nbsp;


## 什么是ChatGPT
* 相信来看这个Repo的朋友都知道ChatGPT，那就不多介绍了 ^_^

## 如何注册

### 1. 需要一个合理的上网环境
* 中国、香港、俄罗斯等地区的IP是不支持的
* 个人正在使用[Renzhe.Cloud](https://renzhe.cloud/auth/register?code=a7JU)，还比较稳定，包月最低CNY 12元

### 2. 准备邮箱
* 任何可以收到邮件的邮箱都可以，QQ邮箱、Gmail等都行

### 3. 准备一个海外手机号
* 如果没有海外手机号，可以使用在线的平台 [sms-activate.org](https://sms-activate.org/cn/info/ChatGPT)（但请注意，实测美国地区成功激活OpenAI账户，印度尼西亚的会失败目前最少需要充值一美金，可用支付宝付款）

### 4. 访问OpenAI注册
* [https://platform.openai.com/login/](https://platform.openai.com/login/)

## 开始体验

### 方式1：ChatGPT官网
* [ChatGPT](https://chat.openai.com/chat) （需要使用海外IP访问，推荐隐私模式）

#### [高级用户] 开通ChatGPT Plus
* 月份20刀，有很多好处，例如速度更快、高可用等。
* 但不支持内地信用卡支持，目前亲测成功的是用[Depay](https://depay.depay.one/web-app/register-h5?invitCode=894306&lang=zh-cn) (iOS请用海外地区App Store下载。欢迎使用我的Depay推荐码：894306）

### 方式2：iOS中快捷方式
* [iOS快捷指令](https://kkgo1999.top/redirect/gpt_shortcut.html)（如遇问题可参考[B站这个视频](https://www.bilibili.com/video/BV1vD4y1n79F/)）

# 如果你还没搞定，你还有如下选择
1. 寻求外援，入微信群交流 [![](https://img.shields.io/badge/WeChat-微信-brightgreen)](https://www.kkgo1999.top/img/kkgo1999.wechat.jpg)
1. 体验新版的微软必应（Bing）搜索
  * 新版Bing有一个非常类似的聊天界面，背后的技术也是由ChatGPT提供。
  * 可以在[这里申请新版Bing](https://www.microsoft.com/zh-cn/edge?form=MA13FJ)的后补，过几天你就会收到一个通知你成功的邮件。
  * 如果你想了解ChatGPT与Bing Chat的区别，可参考[Bing Chat的实测体验（B站）](https://www.bilibili.com/video/BV168411T7bL/)。

# Q&A
### 1. 如何搭建一个基于ChatGPT的微信聊天机器人？
* 目前最安全的方案还是[基于Chrome插件+网页版微信登录的方式](https://www.youtube.com/watch?v=5AC5EywcB6w)，桌面或手机登录的方案非常容易被封禁，不建议尝试

### 2. 遇到“Access Denied, you do not have access to chat.openai.com"
* 更换全局代理，换到国外的IP（非港澳）
* 清理本地的网页缓存
  * 切换到浏览器的 private mode (隐私模式)
  * 在你浏览器的地址栏输入```javascript：```冒号后面复制以下 ```window.localStorage.removeItem(Object.keys(window.localStorage).find(i=>i.startsWith(‘@@auth0spajs’)))```，回车即可
  
### 3. 遇到使用iOS快捷方式没有任何反应
* 如何创建Key：登录https://platform.openai.com/ 后，在 https://platform.openai.com/account/api-keys 这个页面 -> Create new secret key。
* 请先检查账户是否有Credits：登录https://platform.openai.com/ ，在https://platform.openai.com/account/usage 查看credits情况。
