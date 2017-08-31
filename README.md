# 欢迎使用 OhMyWechat 微信号社群运营系统

------

我们理解当一个社群运营的公司，每天面临着无数的粉丝群滴滴答答响个不停的烦恼，无论是已经规模宏大还是初创艰难。也明白销售员不能24小时盯着手机与客户沟通的苦衷。当你每天需要打理无数个用户群的时候，当你每天都需要不断地通过新客户的申请，然后每个人说着同样的话语去推销产品的时候。我想，这个时候，OhMyWechat会祝你一臂之力：

> * Web管理，依托于服务器，可让您的社区运营24小时不断线
> * 清晰明了的控制台：可查看多种数据，为您的社群营销打下数据基础
> * 微信群管：自动记录所有选定的微信群进行管理（邀请入群/触发规则踢出成员/自动智能回复/自动记录重要的对话/全局黑白名单/传话机器人(预计2.0版本开发)）
> * 多账户：（自由切换角色/一键管理/简单快捷的登录操作/单账户个性化配置）
> * 微信群发：（支持定时群发消息/图片-文字-链接-文件自由组合发送/自主选定要发送的对象）
> * 僵尸粉一键辨识： 无打扰自动辨别谁是你的僵尸粉！再也不用担心探测僵尸粉的时候被别人反感被删

行动不如行动，立刻来安装并成为我的粉丝吧！目前OhMyWechat正在紧张开发中，预计9月中旬将会推出第一个稳定开源版供大家尝鲜，如果你想成为开发者的一员，请发Email：sml2h3@gmail.com 欢迎你哦！

### [安装环境]

> 目前测试环境为Ubuntu 16.04 64bit , 理论支持所有能装python3的系统都可以运行。稍后稳定版推出的时候我们会经性详细的测试报告！欢迎大家一起来测试哦！
> Python 3.4 及以上
> pip3

### [最简安装]

 1. 安装 git
 ubuntu: `sudo apt-get install git`
 centos: `sudo yum install git`
 2. 下载代码
`git clone https://github.com/sml2h3/OhMyWechat.git`
 3. 安装支持库
 `cd OhMyWechat`
 `pip3 install -r requirements.txt`
 4. 运行代码
> 测试版运行方式
 `python3 Web.py` (目前Web这样启动，将会在项目开发中根据实际情况不断地调整)
> 正式版运行方式
 `./OhMyWechat.sh`

------

## 开发人员清单

 - [sml2h3]
 - [guzhenping]

### 1. 目前开发进度 [Todo 列表] 2017.8.22

- [x] Web端的界面设计
- [x] 微信账号登录
- [ ] 微信账号长时间保持登录
- [ ] 微信群管
- [ ] 微信僵尸粉检测
- [ ] 微信群发
- [ ] 分布式任务队列
- [ ] 分布式节点建立
- [ ] 系统设置

### 2. 当前版本号

`V 0.01`

### 3. 开源协议
`Apache Licence 2.0`

