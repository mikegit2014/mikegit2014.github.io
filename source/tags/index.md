---
title: tags
date: 2016-11-28 15:38:42
---

<a href="http://notes.iissnan.com/">hexo next 模板  线上预览</a>

```每次更改完 NexT 文档```
都要手动部署到 GitHub Pages，重复的次数多了就显得很麻烦，出错的几率也会变大。文档源码放置在 master 分支，最终部署文件在 gh-pages 分支。当在 master 分支更改某些内容之后，通过运行 gulp dist 来生成最终部署的 HTML 文件到 dist 目录，随后再进入 dist 目录初始化 git 仓库、添加文件、提交文件，最后将提交强制推送到远程 gh-pages 分支（因当心我会误将最终部署的 HTML 文件提交到 master 分支导致源码丢失，我在 GitHub 上把 master 分支给锁定了）。除此之外还有另外一个问题：如果 master 分支有 Pull Requests，我需要先将更新取回本地，然后编译更新再提交回远程 gh-pages 分支。
