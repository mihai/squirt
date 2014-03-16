### Update: Squirt is now covered by an Apache license! 

Apologies to those PRs that got hosed by decoupling squirt.io from the bookmarklet source--resubmit and I'll be happy to engage. 

# Squirt

A speed reading bookmarklet.

## Features

- automatically extracts text from blogs and articles
- manual text selection
- gorgeous
- no external API dependencies

## Contributing

If you want to contribute to this project, follow the below steps to set up
Squirt for local development:

* fork this repository
* clone your fork locally
```
git clone https://github.com/<your_username>/squirt
```
* start a http server in the repo's folder, for example:
```
python -m SimpleHTTPServer 4000
```
* navigate to the website you want to test Squirt on and append `?sq-dev` to the
  URL, which will instruct the bookmarklet to use your local files
* open the bookmarklet from the bookmarks bar

## Sister Projects

* [Spritz](http://www.spritzinc.com/)
* [OpenSpritz](https://github.com/Miserlou/OpenSpritz)
* [OpenSpritz-Android](https://github.com/OnlyInAmerica/OpenSpritz-Android) - An Android Spritz ePub Reader by [@OnlyInAmerica](https://github.com/OnlyInAmerica). Also works with Google Glass!
* [SpritzerTextView](https://github.com/andrewgiang/SpritzerTextView) - An Android Spritz View by [@andrewgiang](https://github.com/andrewgiang)
* [speedread](https://github.com/pasky/speedread) - A terminal Spritzer. by [@pasky](https://github.com/pasky)
* [jetzt](https://github.com/ds300/jetzt) - jetzt, a Spritz Chrome extension by [@ds300](https://github.com/ds300)
* [spread0r](https://github.com/xypiie/spread0r) (previously _gritz_) - A Spritz implementation in Perl by [@xypiee](https://github.com/xypiie/)
* [Spray](https://github.com/chaimpeck/spray) - A Spritzifying website built with OpenSpritz, PHP and Bootstrap. By [@chaimpeck](https://github.com/chaimpeck/)
