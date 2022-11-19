---
title: 协作编辑
description: 和我们一起整理睡前消息的文稿及相关信息
published: true
date: 2022-11-19T13:39:19.815Z
tags: 
editor: markdown
dateCreated: 2022-11-19T13:39:19.815Z
---

# 获取编辑权限
1. 在[登录页](https://archive.bedtime.news/login)创建一个账户并登录（可以通过GitHub注册）。
2. 填写[这个收集表](https://forms.office.com/r/bmFjJpznxt)
3. 等待回复（可主动向`admin@eggroll.club`发邮件/在本页评论催促）。
4. 获得编辑权限后，在[编辑状态](/status)页中查看还未完成整理的文稿并开始整理。
# 格式要求
## 路径
1. **往期文稿**的路径格式应为`/archive/{当前期数所在的以100划分的范围}/期数`。例如：第123期的路径格式应为`/archive/101-200/123`
2. **图片等媒体素材**直接上传至本站服务器。对应的路径格式为`/assets/{当前期数所在的以100划分的范围}/期数-图片序号.[png|jpg]`。格式建议采用`png`或`jpeg`。例如：第101期的第1张图的对应路径应为`/assets/101-200/101-1.png`。如果你使用GitHub进行协作，可以直接将图片添加至对应位置，然后以上述路径进行引用。

## 文件格式
1. 如果你通过本站进行协作，建议使用markdown编辑器整理内容。如果你还未学会使用markdown，可以使用可视化编辑器整理内容。
2. 如果你通过GitHub进行协作，您**需要**以markdown格式发起Pull request。

## 内容格式
1. 与markdown兼容的格式，请直接以markdown格式整理。
2. 如遇颜色等与markdown不兼容的格式，请通过css实现。如果你没有html/css知识，请在评论区或文件注释中说明未实现的格式。
```html
// 常用css
<font color=blue>通过颜色名设置文字颜色</font>
<font color=#1234ab>通过色号设置文字颜色</font>
<font size=3>设置字号</font>
<u>设置下划线</u>
```
3. 请在开头附上当期视频封面，图片序号为0。封面下方请标明当期哔哩哔哩和YouTube链接。格式为：`[哔哩哔哩]({B站链接}) | [YouTube]({YouTube链接})`。链接不能为短链接(需二次跳转的分享链接）或含跟踪参数的链接。
4. 静静的发言请以<font color=indigo>靛蓝色</font>标出（`<font color=indigo>静静的话</font>`），当期主讲人和静静以外的发言可以自选颜色标出。
