Running Heroko from e Heroku server
=========================

Usage
-----

For running Heroko from e Heroku server:

1- install heroku into your pc
2-run : heroku login
3-install a fake heroku app and git push the files to it successfuly
4-run heroku 

1. install heroku into your pc .
2. Run : `heroku login` and login successfully.
3. install a fake heroku app and git push the files to it successfully
4. Run `heroku bash run` and SSH into your app
5. Run `cd `
6.  `git clone https://github.com/Heroku-elasa/heroku-buildpack-toolbelt.git && cd heroku-buildpack-toolbelt/bin && chmod 755 compile `
7. `./compile` and  ` cd && rm -rf heroku-buildpack-toolbelt` 
8. run `export PATH=~/openshifts/app-root/runtime/srv/heroku/bin:$PATH`
9. Wait (This may take at least an hour)
    If you want to see "what's going on, you may tail the log file and watch some shell movie ;)
10.  so you heroku installed in your app and you could do anything with its
11. You can remove the misc content

