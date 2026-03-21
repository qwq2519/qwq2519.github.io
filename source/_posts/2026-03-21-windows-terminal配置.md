---
title: windows-terminal配置
date: 2026-03-21 19:13:40
tags:
  - 软件配置
---
# 下载
win11自带好像，win10可以去官方商店下载，也可以去 https://github.com/microsoft/terminal 下载便携版

然后需要使用pwsh，我先使用windos powershell安装了scoop，然后scoop可以安装pwsh-lts

# 配置

没什么好配置的，有图形化界面可以设置，有一个对于的settings.json在c盘的user/local那边。
我倾向于直接修改配置文件，我的配置文件上传github了

还要安装一个oh-my-posh，美化pwsh的，也是通过scoop安装，然后这个主题需要一个nerd字体，我使用的是[https://www.nerdfonts.com/font-downloads] 里面下载的jetbrainmono nerd字体。 然后再terminal里面 code $PROFILE 打开配置文件，输入 oh-my-posh init pwsh --config $env:POSH_THEMES_PATH\montys.omp.json | Invoke-Expression
montys是主题，可以在oh-my-posh安装目录或者官方进行选择

我一般还会用scoop安装PSReadLine 和zlocation，用来快速跳转的




这是几个参考教程
[https://zhuanlan.zhihu.com/p/678607774]
[https://www.bilibili.com/video/BV1Qa411T7Au/?spm_id_from=333.337.search-card.all.click&vd_source=387f516509a684cc880250a5e722e15f]
