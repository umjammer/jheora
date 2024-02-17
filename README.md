[![Release](https://jitpack.io/v/umjammer/jheora.svg)](https://jitpack.io/#umjammer/jheora)
[![Java CI](https://github.com/umjammer/jheora/actions/workflows/maven.yml/badge.svg)](https://github.com/umjammer/jheora/actions/workflows/maven.yml)
[![CodeQL](https://github.com/umjammer/jheora/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/umjammer/jheora/actions/workflows/codeql-analysis.yml)
![Java](https://img.shields.io/badge/Java-17-b07219)

# jheora

<img alr="theora logo" src="https://upload.wikimedia.org/wikipedia/commons/5/57/Theora_logo_2007.svg" width="129 "/><sub><a href="https://www.theora.org/">© Xiph.Org</a></sub>

Pure Java theora decoder. 

## Install

 * [maven](https://jitpack.io/#umjammer/jheora)

## Usage

## Reference

## TODO

* test

---

# [Original](http://fmj-sf.net/theora-java/getting_started.php)

jheora is part of the Cortado streaming applet available from http://www.flumotion.net/cortado/
While the Cortado applet is GPL, jheora is LGPL.
fluomotion does not distribute a jheora jar, so the sources are included in theora-java.  Additionally,
a few minor changes have been made to make private structure members public, to make the functionality
closer to what theora-jna has.

jheora is dependent on jogg and jorbis from jcraft, available from http://www.jcraft.com/jorbis/
The sources and jars are included here as a convenience.

The same PlayerExample used for theora-jna has been modified to work with jheora.  It takes a URL
as a parameter.

To run it:

```
java -cp ./theora-java.jar:./lib/jheora-patch.jar:./lib/jogg-0.0.7.jar:./lib/jorbis-0.0.15.jar net.sf.theora_java.jheora.example.PlayerExample http://upload.wikimedia.org/wikipedia/commons/d/d0/Apollo_15_liftoff_from_inside_LM.ogg
```


