# WPO Test with Sitespeed.io

## Intro
> Sitespeed.io is an open source tool (Apache License Version 2.0) that helps you analyze your website speed and performance based on performance best practices and timing metrics. It collects data from multiple pages on your website, analyze them using the rules and output the result as HTML or send the metrics to Graphite.

> via https://www.sitespeed.io/

## Dependecies
 - NodeJs
 - Gulp

## How to
- Run in the console
  * <strong>sudo npm install</strong>

- Configure yours <strong>urls</strong> to test and the <strong>budget rules</strong> in <strong>config/testsConfig.js</strong>
  * testTitle: 'Your test Title',
  * url: 'http://yoursiteurl.com',
  * score: 80

- Run test in the console
  * <strong>gulp wpo</strong>

- View results in <strong>/test-results/wpo</strong>

## Other tests
- Google Page Speed Insight
  * In te terminal run: <strong>gulp gspi --url yourUrl</strong>

- Web Page Test
  * In te terminal run: <strong>gulp webpagetest --url yourUrl</strong>

## Posts
[Gulp integration](https://www.npmjs.com/package/gulp-sitespeedio)
(Ankit Singhal - Aug, 2011)

[Test rules](https://www.sitespeed.io/documentation/rules-and-best-practices/)
(Peter Hedenskog - Aug 2015)

[Critical Rendering path](http://calendar.perfplanet.com/2012/deciphering-the-critical-rendering-path/)
(Ilya Grigorik - Dec 2012)

[Css and de Critical Path](http://www.phpied.com/css-and-the-critical-path/)
(Stoyan Stefanov - Jun 2012)

[14 Rules for Faster-Loading Web Sites](http://stevesouders.com/hpws/rules.php)
(Steve Souders - May 2012)

[High Performance Web Sites Blog](http://www.stevesouders.com/)
(Steve Souders)

[Load 3rd party JS asyncrhonously](http://www.phpied.com/3PO/#async)
(Stoyan Stefanov - Jun 2012)

[How to make a performance budget](http://danielmall.com/articles/how-to-make-a-performance-budget/)
(Daniel Mall - Jan 2015)

[Setting a performance budget](http://timkadlec.com/2013/01/setting-a-performance-budget/)
(Tim Kadlec - Jan 2013)

##Follow, up to date
If you’re interested in performance, here are some people and organizations you should be following:
- [Tim Kadlec - @tkadlec](http://twitter.com/tkadlec)
- [Paul Irish - @paul_irish](http://twitter.com/paul_irish)
- [Yesica Perez-Cruz - @yeseniaa](http://twitter.com/yeseniaa)
- [Scott Jehl - @scottjehl](http://twitter.com/scottjehl)
- [Katie Kowalcin - @katiekovalcin](http://twitter.com/katiekovalcin)
- [Ilya Grigorik - @igrigorik](http://twitter.com/igrigorik)

##Collaborators
- [Ignacio Barbieri](https://github.com/ibarbieri)

