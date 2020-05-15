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