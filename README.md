# Hello Git

test



  git config --global user.email "you@example.com"

  git config --global user.name "Your Name"



### …or create a new repository on the command line

```
echo "# hello-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Librarvl/hello-git.git
git push -u origin master   
```



### …or push an existing repository from the command line

```
git remote add origin https://github.com/Librarvl/hello-git.git
git push -u origin master
```



### …or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.



### git pull

git pull origin master



如果出现了如下错误

fatal: refusing to merge unrelated histories

尝试使用

git pull origin master --allow-unrelated-histories





小结：

```
1.
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
  
2.创建一个版本库
  git init
  
3.添加文件到版本库
  git add 文件名					添加到版本库
  git commit -m	"版本信息"			确定添加到版本库
  
4.git status 查看仓库状态
  红色：文件修改修改 未添加到版本库
  绿色：文件添加到版本库 未提交  
  nothing to commit, working tree clean：版本库没有更新的文件
  
5.查看 git 的历史记录
  git log
  git log --pretty=oneline
  
6.回退版本
  git reset --hard 版本 id
  
7.git reflog 显示所有历史记录的版本号

```

