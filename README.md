# study
--1.clone code</br>
git clone http://github.com/littleblackc/study.git</br>
--2.check branch</br>
git branch</br>
git branch -a </br>
--3.create branch</br>
git branch name</br>
--4.go one branch</br>
GIT checkout <name>   </br>
--5.create branch and go one branch eq 3 and 4</br>
git checkout -b name</br>
--6.add new file</br>
git add file</br>
--7.commit</br>
git commit -m "comments"</br>
--8.merge branch</br>
git merge branch name</br> 
eg. merge dev code to maaster. get merge dev</br>
--9.check status</br>
git status</br>
--10.check different</br>
git diff
--11.test 
git remote -v
--12.update local code from remote
git pull origin dev ----from branch dev
git pull origin master ---from branch master
--13.return previos version
git checkout -- file
--14.generate ssh
(1)check exist ssh
~/.ssh
(2)generate the key
ssh-keygen -t rsa -C "haiyan.xu.vip@gmail.com"
(3)add the key
id_rsa.pub
--15.change url(from https to ssh)
git remote origin git@github.com:littleblackc/study.git
--16.merge
git merge --no-off -m "comments" branch
--17.check log
git log --graph --pretty=oneline --abbrev-commit
18.fixed bug</br>
(1)git stash</br>
(2)git stash apply + git stash drop =git stash pop
(3)git stash list
19.boris add
20.tom add


Merge Code
1.checkout local branch
git branch
2.checkout remote branch
git branch -a
3.update code from branch
git pull origin dev --- update remote dev code
4.swith branch
git checkout master  -- swith to local branch master
5.update remote master code
git pull origin master
6.merge dev code to master
git merge dev
7.pull code to remote
git push origin master

Download Code
1.init git
git remote add upstream https://github.com/...
2.git remote content
git fetch upstream/master

<h1>NPM Install</h1>
npm install -g gulp --registry=https://registry.npm.taobao.org
