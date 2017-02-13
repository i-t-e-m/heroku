# Hello heroku

$ heroku login

Email: name@sample.com

Password (typing will be hidden):

### heroku run !!

$ heroku create
Creating app... done, appName
https://appName.herokuapp.com/ | https://git.heroku.com/appName.git

$ git push heroku master
Counting objects: 9, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (9/9), 748 bytes | 0 bytes/s, done.
Total 9 (delta 1), reused 0 (delta 0)
(...snip)
remote: Verifying deploy... done.
To git@heroku.com:appName.git
 * [new branch]      master -> master

$heroku open

### my apps show

$ heroku apps

### my apps delete

$ heroku apps:destroy --app appName --confirm appName