# gitflow
Kristians Egle
$ git checkout master
$ git merge --no-ff release-1.2
$ git tag -a 1.2
$ git checkout -b hotfix1_1 master
$ ./bump-version.sh 1.2.1
$ git commit -a -m "Bumped version number to 1.2.1"
$ git commit -m "Fixed severe production problem"
$ git checkout master
$ git merge --no-ff hotfix1_1
$ git tag -a 1.2.1
