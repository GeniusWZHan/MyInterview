# Git操作说明

1. 初始化文件夹

本章进行文件夹的初始化工作，具体操作如下：

```java
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GeniusWZHan/MyInterview.git
git push -u origin main
```

2. 在本地git配置账号信息

```java
## 查看git配置信息
git config --list //所有配置列表查看
git config user.name // 用户名
git config user.password //用户名密码
git config user.email // 用户邮箱

## 设置用户邮箱
git config --global user.email "XX.com" 
## 设置用户名
git config --global user.name "GeniusWZHan"
## 设置用户名密码
git config --global user.password XXXX
```

3. 查看git提交记录

```java
## 查看提交日志
git log --oneline // 查看提交记录 只看一行
```

4. 删除本地提交记录

```java
## ？？
git reset --hard HEAD~1 //？？	
```

