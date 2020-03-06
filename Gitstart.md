# Git入门命令简章
## 1. Git 六行配置代码 本地建仓
### 必须通过Cmder配置命令：
```
    git config --global user.name RenLishisan
    git config --global user.email renshisan@qqcom
    git config --global push.default simple
    git config --global core.quotepath false
    git config --global core.editor "code --wait"
    git config --global core.autocrlf input
```
### 注意：上面的英文名和邮箱跟 GitHub 没有关系。可以跟 GitHub 的用户名和邮箱保持一致，也可以不一致。执行此代码需要的到“Cmder”上面通过Bash 终端执行。

## 2. 常用Git命令
   * ` git config --global --list `  //安装检测执行命令
   * ` git init ` //初始化
   * ` mkdir demo ` //创建新的目录 demo为目录名
   * ` touch index.html ` //创建新的html文件
   * ` Code index.html ` //通过VScode打开html
   * ` Code .`  //加一个“.”则表示通过VScode打开当前目录
   * ` git status ` //查看被改变未提交的文件，文件名已红色变成绿色表示文件待提交。
   * ` git add index.html ` // 向仓库申请提交index.html文件
   * ` git commit -v ` //提交，会自动打开VScode 在里面说明提交理由 字符串里如果有空格就要用引号包起来
   * ` git commit -m `(备注)  //快速提交，直接备注版本号
   * ` git reset --hard ac8c36 ` //回到历史版本 最后带上历史版本ID号
   * ` git log ` //查看当前提交历史版本
   * ` git reflog ` //查看6所有提交版本
   * ` .gitignore ` //在VScode中创建此程序，里面写入不向仓库提交的文件
   * ` git branch x ` //只是创建一个分支，可以创造平行时间线x 术语叫做[分支]”x”可以之定义
   * `git checkout x ` //切换到”x”分支
   * ` git chechout master ` //回到主分支
   * ` git merge x ` //合并分支”x”、
   * GitHub上传命令：先获取github的仓库地址进行连接，然后通过` git push -u origin master `进行上传至“master”主线
### 以上命令主要使用`Git` `Cmder` `Vscode`等配合使用。
## 如果觉得本篇文章对你有帮助欢迎点击 [荏狸十三的主页](https://www.github.com/RenLishisan)  查看更多入门教程！ 
## 感谢下方“写代码啦”提供教学支持
![写代码啦](https://static.xiedaimala.com/xdml/cdn/assets/black-logo-25c84e68b3770b75580e7dbba2b77ce68f7fc1794d35afac32057c2d4ea4c498.png)
