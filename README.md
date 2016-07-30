# Git学习启示录
*Copy自廖雪峰的Web*

**by ZTook   <ztook@outlook.com>**
![alt text](/logo.jpg  "寡人之LOGO")

[廖雪峰同志的内心世界][001]
[001]: http://www.liaoxuefeng.com/wiki  "廖雪峰同志的内心世界"
[疯狂的推酷](http://www.tuicool.com  "疯狂的推酷")
[001]: http://www.xxx.com  "廖雪峰同志的内心世界"

## Git之整装出发
1. git init
2. git add
3. git commit
4. git diff
```
git log --graph --pretty=oneline --abbrev-commit
git diff commit1-id commit2-id
git diff commit1-id commit2-id >> conflict.log
```
5. git checkout -- file
6. git reset HEAD file
7. git rm file
8. git checkout -b dev
   = git branch dev
     git checkout dev
9. git branch

> 坚定不移的时光分割线
>> 再次坚定而磐石无转移地分割

*******
## Git之合并操作
10. git merge dev
11. git log / git reflog  

~~老大我错了~~  

12. git log --graph --pretty=oneline --abbrev-commit
｀｀｀
git log --graph --pretty=oneline --abbrev-commit
｀｀｀
13. git branch -d feature1
14. git stash
15. git stash list
16. git stash pop
    = git stash apply
      git stash drop
17. git branch -d feature-vulcan / git branch -D feature-vulcan
18. git remote -v
19. git push origin master/dev
20. git checkout -b dev origin/dev
21. git branch --set-upstream dev origin/dev
22. git tag v1.0
23. git tag
24. git tag v0.9 6224937
25. git show tag-name
26. git server-self:

|行为   |命令                                                              |说明|
|:----:|:----------------------------------------------------------------|:--|
|安装git|sudo apt-get install git                                         |   |
|创建用户|sudo adduser git                                                 |   |
|创建证书|then，创建证书登录：收集所有需要登录的用户的公钥，就是他们自己的id_rsa.pub文件|   |
|导入证书|把所有公钥导入到/home/git/.ssh/authorized_keys文件里，一行一个          |   |
|创建仓库|sudo git init --bare sample.git                                  |   |
|赋予权限|sudo chown -R git:git sample.git                                 |   |
|下载仓库|git clone git@server:/srv/sample.git                             |   |

*******
## Git之远程操作
27. git remote add origin git@github.com:ZTook/markdown_test.git
28. git push master
29. git fetch
