# Gitѧϰ��ʾ¼ ��
*Copy����ѩ���Web*

**by ZTook<ztook@outlook.com>**
![alt text](/logo.jpg  "����֮LOGO")

[��ѩ��ͬ־����������][001]
[001]: http://www.xxx.com  "��ѩ��ͬ־����������"
[�����ƿ�](http://www.tuicool.com  "�����ƿ�")
[001]: http://www.xxx.com  "��ѩ��ͬ־����������"

## Git֮��װ���� ##
1. git init
2. git add
3. git commit
4. git diff
5. git checkout -- file
6. git reset HEAD file
7. git rm file
8. git checkout -b dev
   = git branch dev
     git checkout dev
9. git branch
10. git merge dev
11. git log
12. git log --graph --pretty=oneline --abbrev-commit
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
      sudo apt-get install git
      sudo adduser git
      then������֤���¼���ռ�������Ҫ��¼���û��Ĺ�Կ�����������Լ���id_rsa.pub�ļ���
      �����й�Կ���뵽/home/git/.ssh/authorized_keys�ļ��һ��һ����
      sudo git init --bare sample.git
      sudo chown -R git:git sample.git
      git clone git@server:/srv/sample.git