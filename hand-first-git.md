简单地记录学习Git的过程。

# 什么是Git？

Git是一个分布式文件版本管理系统。“版本管理系统”是一种能追踪文件更改，保存文件历史版本的系统。
借助Git，能够方便地回顾追踪的文件的每一次修改，还可以方便地还原文件到某一个特定的版本。

要使用Git，首先要理解仓库的概念。

仓库是保存所有文件的位置。只有被放到仓库中的文件才能被Git跟踪。

https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

# 什么是GitHub？

GitHub是托管服务，对应Git中远端的概念。

# 如何使用Git

## 第一步 设置自己的用户信息

```bash
git config --global user.name catchwind
git config --global user.email 594782271@qq.com

```

## 第二步 新建Git仓库

```bash
git init

```
## 第三步 新建文件并追踪

```bash
git add <file>
```
