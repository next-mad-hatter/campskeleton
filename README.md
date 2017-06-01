weighted straight skeleton implementation in java.

allows negative weights for offsetting in either direction. implementation of [Felkel's](http://www.dma.fi.upm.es/mabellanas/tfcs/skeleton/html/documentacion/Straight%20Skeletons%20Implementation.pdf) algo with robustness - described [here](http://twak.blogspot.com/2009/05/engineering-weighted-straight-skeleton.html).

[![](http://farm5.static.flickr.com/4006/4709590538_76e5c9ce6f.jpg)](http://www.flickr.com/photos/twak/4709590538/)

run the [jar] (https://github.com/twak/campskeleton/blob/master/campskeleton-0.0.1-SNAPSHOT-jar-with-dependencies.jar?raw=true) with

```
java -jar siteplan-0.0.1-SNAPSHOT-jar-with-dependencies.jar
```

requires [my jutils](https://github.com/twak/jutils) to be installed (with 'mvn compile install'). then the command 'mvn package' should build a jar.

there's a primative gui interface. [video](http://www.youtube.com/watch?v=2twcln3_7Y8). use left mouse button to move points and control-click to add new points.

main UI class is [org.twak.camp.debug.CampSkeleton](https://github.com/twak/campskeleton/blob/master/src/org/twak/camp/debug/CampSkeleton.java). 

[example code usage](https://github.com/twak/campskeleton/blob/wiki/headless.md)

i believe i own the license to all code in this release, hasn't been vetted for a while tho, so go carefully.