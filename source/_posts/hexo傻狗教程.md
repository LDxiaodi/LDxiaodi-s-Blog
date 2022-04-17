---
title: hexo傻狗教程
categories: 技术备忘录
tag:
- 干货
- 备忘录
---

- 博客
- 技巧分享

创建hexo静态网页：

[官方文档]([文档 | Hexo](https://hexo.io/zh-cn/docs/))

**更新hexo文章：**

前提：GitHub已经成功git完毕

安装一个东西：

```
npm install hexo-deployer-git --save
```

输入一个东西：

```
cd .deploy_git
git push -f
```

打开网页根目录，右击“用Windows终端”打开，然后输入这个：

```
hexo cl | hexo d -g
```

等待成功，不成功一直试就行了。然后等待GitHub pages完成部署。