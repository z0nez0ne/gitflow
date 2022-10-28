# gitflow
Kristians Egle
$ git checkout develop
$ git merge --no-ff feat-uzd
$ git branch -d feat-uzd
$ git push origin develop
$ git checkout -b release-1.2 develop
$ ./bump-version.sh 1.2
$ git commit -a -m
$ git checkout develop
$ git merge --no-ff release-1.2
