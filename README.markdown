# Nginx and Wordpress running on Heroku

Build anything you want on Heroku.  Experimental proof of concept.

```
heroku create nginx-on-heroku -s cedar --buildpack https://github.com/mchung/heroku-buildpack-nginx
git push heroku master
```

* `src` - Latest nginx and php source code
* `www` - Latest wordpress

Codebases have been modified to support Heroku.

You probably want to look at [Wordpress-on-Heroku](http://github.com/mchung/wordpress-on-heroku) or [heroku-buildpack-wordpress](http://github.com/mchung/heroku-buildpack-wordpress)

