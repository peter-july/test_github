1. code.
2. Practice.
3. Build.
4. Research. 
5. Write.

------------------------

test the use of user.name and user.email of git:  
1. set valid name, valid email, can get committer. 
2. set invalid name, valid email, can get committer.
3. set valid name, invalid email, cann't get committer.
4. set invalid name, invalid email, cann't get committer.  

So must set a valid email before you commit a change. 

------------------------
about branch usage1: 
1. create a new branch. 'git checkout -b tmp_b'
2. make some modification at this branch.
3. push tmp_branch to origin tmp_branch. 'git push -u origin tmp_branch:tmp_branch'
4. then we want to merge origin/tmp_branch to origin/main
5. create a pull request at github.
6. merge this pull request to main at github.
7. delete origin/tmp_branch at github.
8. at local, switch to master and git pull. 'git checkout master; git pull'
9. delete lacal tmp_branch. 'git branch -d tmp_branch'

about branch usage2:


