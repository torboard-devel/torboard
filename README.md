TORboard - A lightweight and full featured PHP imageboard used on Uroborosu
===========================================================================
**TORboard does not offer ANY kind of support - use with caution**

About
------------
TORboard is a free light-weight, fast, highly configurable and user-friendly
imageboard software package based on vichan. It is written in PHP and has few dependencies.

History
------------
TORboard is a fork of [vichan](https://github.com/vichan-devel/vichan) which is in turn a fork of (now defunc'd) [Tinyboard](http://github.com/savetheinternet/Tinyboard),
a great imageboard package, actively building on it and adding a lot of features and other
improvements.

### Maintainer timeline
1. [@torboard-devel](https://github.com/torboard-devel) (2023 - present)
1. [@h00j](https://github.com/h00j) (2021 - present) (vichan dev, not affiliated with TORboard)
2. [@ctrlcctrlv](https://github.com/ctrlcctrlv) (2017 - 2021)
3. [@czaks](https://github.com/czaks) (2014 - 2017) (The author of vichan fork)
4. [@savetheinternet](https://github.com/savetheinternet) (2010 - 2014) (The creator of Tinyboard)

Requirements
------------
1.	PHP >= 5.4 (we still try to keep compatibility with php 5.3 as much as possible)
        PHP 7.0 is explicitly supported. PHP 7.2 works as well, but may cause as yet unreported bugs.
2.	MySQL/MariaDB server
3.	[mbstring](http://www.php.net/manual/en/mbstring.installation.php) 
4.	[PHP GD](http://www.php.net/manual/en/intro.image.php)
5.	[PHP PDO](http://www.php.net/manual/en/intro.pdo.php)
6.	A Unix-like OS, preferrably FreeBSD or GNU/Linux

### Recommended
1.	MySQL/MariaDB server >= 5.5.3
2.	ImageMagick (command-line ImageMagick or GraphicsMagick preferred).
3.	~~[APC (Alternative PHP Cache)](http://php.net/manual/en/book.apc.php)~~,
	[APCu (Alternative PHP Cache)](http://php.net/manual/en/book.apcu.php),
	[XCache](http://xcache.lighttpd.net/),
	[Memcached](http://www.php.net/manual/en/intro.memcached.php) or
	[Redis](https://redis.io/docs/about/)

Contributing
------------
You can contribute to vichan by:
*	Developing patches/improvements/translations and using GitHub to submit pull requests
*	Providing feedback and suggestions
*	Writing/editing documentation

Installation
-------------
Follow the same steps as you to insall vichan.

Oekaki
------
TORboard makes use of [wPaint](https://github.com/websanova/wPaint) for oekaki. After you pull the repository, however, you will need to download wPaint separately using git's `submodule` feature. Use the following commands:

```
git submodule init
git submodule update
```

To enable oekaki, add all the scripts listed in `js/wpaint.js` to your `instance-config.php`.

WebM support
------------
Read `inc/lib/webm/README.md` for information about enabling webm.

vichan API
----------
vichan provides by default a 4chan-compatible JSON API. For documentation on this, see:
https://github.com/vichan-devel/vichan-API/ .

License
--------
See [LICENSE.md](http://github.com/vichan-devel/vichan/blob/master/LICENSE.md).

