ComicBookMaker
==============
Script to fetch webcomics and use them to create ebooks.

[![Build Status](https://travis-ci.org/SylvainDe/ComicBookMaker.svg?branch=master)](https://travis-ci.org/SylvainDe/ComicBookMaker)



Longer explanation
------------------
Web crawlers are defined to retrieve comic information and store them into files. This can then be used to generated ebooks.

Command-line interface
----------------------
`comicbookmaker.py` takes multiple arguments.
 * `--comic` (or `-c`) can be used to tell which comic(s) is/are to be considered (defaults to all of them).
 * `--action` (or `-a`) specifies which actions are to be performed on these comics : update (default behavior), book, etc.

Comics supported
----------------
 * [Abstruse Goose](http://abstrusegoose.com)
 * [Tales of Absurdity](http://talesofabsurdity.com)
 * [Anything Comic](http://www.anythingcomic.com)
 * [Argyle Sweater](http://www.gocomics.com/theargylesweater)
 * [Amazing Super Powers](http://www.amazingsuperpowers.com)
 * [Aurel](http://aurel.blog.lemonde.fr)
 * [Jim Benton](http://www.gocomics.com/jim-benton-cartoons)
 * [Berkeley Mews](http://www.berkeleymews.com)
 * [Biter Comics](http://www.bitercomics.com)
 * [Every Day Blues](http://everydayblues.net)
 * [Boulet Corp](http://www.bouletcorp.com)
 * [Boulet Corp English](http://english.bouletcorp.com)
 * [Break Of Day](http://www.gocomics.com/break-of-day)
 * [Brevity](http://www.gocomics.com/brevity)
 * [BuniComics](http://www.bunicomic.com)
 * [ButterSafe](http://buttersafe.com)
 * [Calvin and Hobbes](http://marcel-oehler.marcellosendos.ch/comics/ch/)
 * [Calvin and Hobbes (from GoComics)](http://www.gocomics.com/calvinandhobbes)
 * [Channelate](http://www.channelate.com)
 * [Chuckle-A-duck](http://chuckleaduck.com)
 * [Victims Of Circumsolar](http://www.victimsofcircumsolar.com)
 * [Over Compensating](http://www.overcompensating.com)
 * [Completely Serious Comics](http://completelyseriouscomics.com)
 * [Cyanide and Happiness](http://explosm.net)
 * [Depressed Alien](http://depressedalien.com)
 * [According To Devin](http://accordingtodevin.tumblr.com)
 * [Dilbert](http://dilbert.com)
 * [Dinosaur Comics](http://www.qwantz.com)
 * [Disco Bleach](http://discobleach.com)
 * [The Dog House Diaries](http://thedoghousediaries.com)
 * [Extra Fabulous Comics](http://extrafabulouscomics.com)
 * [My Extra Life](http://www.myextralife.com)
 * [Fat Awesome](http://fatawesome.com/comics)
 * [Cartooning For Peace](http://cartooningforpeace.blog.lemonde.fr)
 * [Fowl Language Comics](http://tapastic.com/series/Fowl-Language-Comics)
 * [Garfield](http://garfield.com)
 * [The Gentleman Armchair](http://thegentlemansarmchair.com)
 * [Xavier Gorce](http://xaviergorce.blog.lemonde.fr)
 * [Happle Tea](http://www.happletea.com)
 * [Horovitz Classic](http://www.horovitzcomics.com)
 * [Horovitz New](http://www.horovitzcomics.com)
 * [Invisible Bread](http://invisiblebread.com)
 * [Irwin Cardozo](http://irwincardozocomics.tumblr.com)
 * [LastPlaceComics](http://lastplacecomics.com)
 * [Loading Artist](http://www.loadingartist.com/latest)
 * [Mike Luckovich](http://www.gocomics.com/mikeluckovich)
 * [Lunar Baboon](http://www.gocomics.com/lunarbaboon)
 * [Mercworks](http://mercworks.net)
 * [Lonnie Millsap](http://www.lonniemillsap.com)
 * [Infinite Monkey Business](http://infinitemonkeybusiness.net)
 * [Mr. Lovenstein](http://www.mrlovenstein.com)
 * [NeDroid](http://nedroid.com)
 * [Octopuns](http://www.octopuns.net)
 * [Off The Mark](http://www.gocomics.com/offthemark)
 * [Oglaf [NSFW]](http://oglaf.com)
 * [Endless Origami](http://endlessorigami.com)
 * [Oscillating Profundities](http://tapastic.com/series/oscillatingprofundities)
 * [Pain Train Comics](http://paintraincomic.com)
 * [Perry Bible Fellowship](http://pbfcomics.com)
 * [Peanuts](http://www.gocomics.com/peanuts)
 * [Pearls Before Swine](http://www.gocomics.com/pearlsbeforeswine)
 * [Penmen](http://penmen.com)
 * [PhD Comics](http://phdcomics.com)
 * [Pictures in Boxes](http://www.picturesinboxes.com)
 * [Plantu](http://plantu.blog.lemonde.fr)
 * [Poorly Drawn Lines](http://poorlydrawnlines.com)
 * [Ted Rall](http://rall.com/comic)
 * [Michael Ramirez](http://www.gocomics.com/michaelramirez)
 * [Gone Into Rapture](http://www.goneintorapture.com)
 * [Sarah Andersen (from GoComics)](http://www.gocomics.com/sarahs-scribbles)
 * [Sarah Andersen (from Tapastic)](http://tapastic.com/series/Doodle-Time)
 * [Scandinavia And The World](http://satwcomic.com)
 * [Saturday Morning Breakfast Cereal](http://www.smbc-comics.com)
 * [Something Of That Ilk](http://www.somethingofthatilk.com)
 * [Things in squares](http://www.thingsinsquares.com)
 * [Sunny Street](http://www.gocomics.com/sunny-street)
 * [Thor's Thundershack](http://www.thorsthundershack.com)
 * [Three Word Phrase](http://threewordphrase.com)
 * [Tom Toles](http://www.gocomics.com/tomtoles)
 * [Toon Hole](http://www.toonhole.com)
 * [Tubey Toons](http://tubeytoons.com)
 * [Tubey Toons (from Tapastic)](http://tapastic.com/series/Tubey-Toons)
 * [Vegetables For Dessert](http://tapastic.com/series/vegetablesfordessert)
 * [Vidberg -l'actu en patates](http://vidberg.blog.lemonde.fr)
 * [Warehouse Comic](http://warehousecomic.com)
 * [Wondermark](http://wondermark.com)
 * [Matt Wuerker](http://www.gocomics.com/mattwuerker)
 * [WuMo](http://www.gocomics.com/wumo)
 * [xkcd](http://xkcd.com)
 * [The Awkward Yeti](http://theawkwardyeti.com)
 * [Zen Pencils](http://zenpencils.com)
 * [Zep World](http://zepworld.blog.lemonde.fr)
 * [Znoflats Comics](http://tapastic.com/series/Znoflats-Comics)
