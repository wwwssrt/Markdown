# 总结20190615

今天和BB一起学习了git github 和 markdown 并且学习了使用VS来操作. Git 和 Github 常像 Java 和 Javascript 被 弄混. 他们之间的相同之处在于两者都是被用于代码甚至文档的版本管理的应用。通过实时更新和汇报冲突来，合作方得以避免重复更改相同内容以导致更新的丢失。区别在于Git 是一个位于本地的软件，其主要目的是帮助开发者更新版本， 而github提供云端服务，将不同的开发者通过云端联系起来。

## Git 相关

- 创建文件与项目
  
- 将文件add - commit - push到云端
- 冲突的产生和解决

### Workflow
1. 本地新建文件夹
2. git init
3. 关联到git
   1. 右键关联（Git Bash here)
   2. 直接使用GitHub desktop 关联
   3. 直接根据云端创建repo后的指示
4. 关联到云端repo(根据github提示或直接使用desktop)
5. 创建文件 -> git status -> git add <filename> -> git status -> git commit -m "信息" -> git push
6. 同步云端文件 git pull
   1. 注意conflict的解决
7. 时刻注意github返回的信息并根据信息提示修改

## Github 相关

- 在云端创建项目并clone到本地
- 邀请编辑

## Markdown 作为一种文本编辑软件

- Markdown 作为一种文本编辑软件可以全程使用键盘操作而使得编辑者不需要分心于其它操作。通过简单的代码可以实现字体、字号、标题分级操作，甚至可以创造表格与todo list.

## 使用VS的操作

- Visual studio 是一种编辑器，可以通过添加插件来完成多种编程语言的编辑，也可以通过terminal来操作git上传至github的流程。


[简明指南](http://rogerdudler.github.io/git-guide/index.zh.html)
[猴子学GitHub](https://backlog.com/git-tutorial/cn/intro/intro1_1.html)
[python学习](http://www.krivers.net/15112-f17/schedule.html)