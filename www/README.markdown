# Wordpress on Heroku

Wordpress on Heroku--you know, when you want to run Wordpress on Heroku.

## List of improvements

* **SMTP over Sendmail** - Make sure to install the SendGrid addon.
* **MySQL** - Make sure to install the ClearDB addon.
* **SSL everywhere** - Added FORCE_SSL_LOGIN and FORCE_SSL_ADMIM.

## Can I use this or what?

This is a work in progress. There are a few low traffic blogs that I run on production and since I've done it more than once, I decided to script the entire process.

There are a few things I want to get out the door before making an official (non-beta) release.

## Roadmap (todo)

* Use nginx (custom buildpack)
* Handle zlib requirements (custom buildpack)
* Handle image uploads to S3 instead (plugin or custom code)
* Automatically update repository to latest stable Wordpress

## I thought Heroku was only for Ruby applications?

Not anymore. Heroku's latest offerings (See [Celadon Cedar stack](http://devcenter.heroku.com/articles/cedar)) makes it easy (well, easyish) for developers to install and run any language, or actually any service.

## Related

Automate this even more with [wordup](http://github.com/mchung/wordup), my bash script that setups Wordpress on Heroku in 60 seconds.