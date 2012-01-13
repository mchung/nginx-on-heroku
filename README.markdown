# Nginx and Wordpress running on Heroku

Experimental proof of concept.

```
heroku create nginx-on-heroku -s cedar --buildpack https://github.com/mchung/heroku-buildpack-nginx
git push heroku master
```

`src` - Latest nginx and php source code
`www` - Latest wordpress

The codebases have been modified to support Heroku.

In the case of Wordpress, please refer to one of my other projects [Wordpress-on-Heroku](http://github.com/mchung/wordpress-on-heroku)

## TODO

* Use [http://github.com/heroku/vulcan](vulcan) to prebuild binaries.
* Harden nginx
* Tune nginx 