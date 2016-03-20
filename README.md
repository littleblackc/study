# study
--1.clone code
git clone http://github.com/littleblackc/study.git
--2.check branch
git branch
--3.create branch
git branch name
--4.go one branch
--5.create branch and go one branch eq 3 and 4
git checkout -b name
--6.add new file
git add file 
--7.commit
git commit -m "comments"
--8.merge branch
git merge branch name 
eg. merge dev code to maaster. get merge dev
--9.check status
git status
--10.check different
git diff
--11.
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
--16.for dev test



