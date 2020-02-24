1. 进https://github.com/ new repository
Repository name:vue-online
Discription:上传项目
Add.gitignore:Node Add a license：Mis license
create repository
Clone or Download复制链接

1. npm run serve 开发
2. npm run build 打包到dist
将dist/index.html中有关路径的都改成相对路径（./)

新建分支并且换到分支中
git checkout -b 新分支名
github托管一个静态的网站，要新建gh-pages的分支(开源项目发布分支)
来到根目录vue-shop先提交第一部分 
将所有文件都提交到暂存区：git add .
再写一个注释：git commit -m ''
上传到主分支：git push origin master
dist没有上传 是.gitignore文件的问题

git checkout master回到master分支
git branch 查看分支

gh-pages
MIT github master 最稳定版本
gh-pages分支上把dist目录下的代码搞过去

把dist代码留下 其他的删除
open in folder

git status查看最近做了什么，删了什么
再做一次提交