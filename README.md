![kenzo github stats](https://github-readme-stats.vercel.app/api?username=HDragon8&show_icons=true&theme=merko)
<div align="center">
<h1 align="center">同步上游分支代码</h1>
<img src="https://img.shields.io/github/issues/HDragon8/led_packages?color=green">
<img src="https://img.shields.io/github/stars/HDragon8/led_packages?color=yellow">
<img src="https://img.shields.io/github/forks/HDragon8/led_packages?color=orange">
<img src="https://img.shields.io/github/license/HDragon8/led_packages?color=ff69b4">
<img src="https://img.shields.io/github/languages/code-size/HDragon8/led_packages?color=blueviolet">
</div>


#### led_packages

*  复制自kenzok8：https://github.com/kenzok8

*  常用OpenWrt软件包源码合集，同步上游更新！

*  通用版luci适合18.06与19.07

*  关于有好的插件请在issues提交

*  感谢以上github仓库所有者！


##### 关于Secrets、TOKEN的小知识


1. 首先需要获取 **Github Token**: [点击这里](https://github.com/settings/tokens/new) 获取,

 `Note`项填写一个名称,`Select scopes`不理解就**全部打勾**,操作完成后点击下方`Generate token`

2. 复制页面中生成的 **Token**,并保存到本地,**Token 只会显示一次!**

3. **Fork** 我的`led_packages`仓库,然后进入你的`led_packages`仓库进行之后的设置

4. 点击上方菜单中的`Settings`,依次点击`Secrets`-`New repository secret`

其中`Name`项填写`ACCESS_TOKEN`,然后将你的 **Token** 粘贴到`Value`项,完成后点击`Add secert`

* 对应`.github/workflows`目录下的`yml`工作流文件里的`ACCESS_TOKEN`名称（依据自己yml文件修改）

* 在仓库`Settings->Secrets`中添加 `SCKEY `可通过[Server酱](http://sc.ftqq.com) 推送编译结果到微信

* 在仓库`Settings->Secrets`中添加 `TELEGRAM_CHAT_ID, TELEGRAM_TOKEN `可推送编译结果到`Telegram Bot`




#### 使用方式（三选一）：

1. 先cd进package目录，然后执行

```bash
 git clone https://github.com/HDragon8/led_packages
```
2. 或者添加下面代码到feeds.conf.default文件

```bash
 src-git small8 https://github.com/HDragon8/led_packages
```
3. lede/下运行 或者openwrt/下运行

```bash
git clone https://github.com/HDragon8/led_packages package/led_packages
```











