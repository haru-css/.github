# Solas CSS 🍃

[Tachyons](http://tachyons.io/) is a wonderfully conceived CSS framework. At a time when monolithic CSS libraries like Bootstrap were king, Tachyons was a refreshing change, as a well rationalised suite of lightweight, single-purpose, highly versatile utility classes that are easy to use and debug.

While the concept of Object Orientated or Utility Class based CSS aproaches were being explored, noteably by [Nicole Sullivan](https://twitter.com/stubbornella) as [early as 2007](https://twitter.com/stubbornella/status/1471213109767405568), the first commit on what would become Tachyons, was made by Maine native Adam Morse (aka mrmrs) on [Jan 18, 2014](https://github.com/tachyons-css/tachyons/commits?after=139156c724f8b3e4155ca75d8e353a172c541c36+1170). From there Tachyons evolved at a significant pace for several years and gained wide popularity. Over the intervening years development of Tachyons has tapered off, and other frameworks have risen in prominence.

In building Solas, my chief aim has been to analyse and consider the many design decisions and compromises the contributors to Tachyons made when crafting the original framework.

While compiled Tachyons is still very useable, much of the tooling around its ecosystem has suffered from breaking dependencies which prevent new builds. Solas aims to minimise this complexity using booring tech, with a monolithic Sass-first approach. Once a flexible and modern Sass foundation has been crafted, new modules can be added to address browser features available since Tachyons' last stable release.

#### Adam Morse: Devshop, London June 2016
[![Adam Morse explainsTachyons CSS at Devshop London, June 2016](https://img.youtube.com/vi/r56fRaWth58/0.jpg)](https://www.youtube.com/watch?v=r56fRaWth58)

Solas is a fork of Tachyons and has no affiliation with the parent project.
