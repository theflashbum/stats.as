stats.as
========

#### Actionscript Performance Monitor ####

![stats_as.png](http://github.com/mrdoob/stats.as/raw/master/assets/stats_as.png)

This class provides a simple info box that will help you monitor your code performance.

* FPS Frames per second, how many frames were rendered in 1 second. The higher the number, the better.
* MS Milliseconds needed to render a frame. The lower number, the better.
* MEM Memory your code is using, if it increases per frame is VERY wrong.
* MAX Maximum memory the application reached.

### How to use ###

	addChild( new Stats() );

### Controls ###

* **LEFT CLICK** on the top-half/bottom-half part of the panel to increase/decrease the movie FPS limit.

### Download ###

[Stats.as](http://github.com/mrdoob/stats.as/raw/master/src/Stats.as)

### Change Log ###

2009 10 22 - v**2.2**

* FlipX of graph to be more logic.
* Destroy on Event.REMOVED_FROM_STAGE (thx joshtynjala)


2009 03 28 - v**2.1**

* Theme support.


2009 02 21 - v**2.0**

* changed text system
* added MAX value (Max memory reached). very useful for spotting memory leaks
* removed player version on roll over (let me know if this is a bad idea)
* simplified


2009 02 07 - v**1.5**

* onRemovedFromStage() (thx huihuicn.xu)


2008 12 14 - v**1.4**

* Code optimisations, should take even less CPU
* Fixed ugly drawing when transparent (thx makc.the.great)
* Added Version info on Mouse Over.
