FORKED version
==============

I strongly recommend you DON'T use this library. This is a heavily forked version of socialauth 4.5 ( https://github.com/3pillarlabs/socialauth ).


Problems with this library:
 - it has no tests, so touching anything is really dangerous
 - HTTP client is hard-coded, so not configurable.
 - it depends on specific (bad) behaviour of old version of org.json. Newer versions fail to parse output. What is worse: the source of the required version (json-20090211) is not available (seems to be lost). I embedded version 20080701 inside the com.flozano.socialauth package, which seems to work.

Believe me, you want to stay away from this.
