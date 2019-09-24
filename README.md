# n5-blosc [![Build Status](https://travis-ci.com/saalfeldlab/n5-blosc.svg?branch=master)](https://travis-ci.com/saalfeldlab/n5-blosc)
Blosc compression for N5.

This library wraps the [JBlosc](https://github.com/lasersonlab/jblosc) interface for C-Blosc as an [N5 compression interface](https://github.com/saalfeldlab/n5/blob/master/src/main/java/org/janelia/saalfeldlab/n5/Compression.java).  [JBlosc](https://github.com/lasersonlab/jblosc) depends on `libblosc1`.  On Ubuntu, install with:
```
sudo apt-get install -y libblosc1
```
On other platforms, please check the [installation instructions](https://github.com/lasersonlab/JBlosc/blob/master/README.md) for [JBlosc](https://github.com/lasersonlab/jblosc).

Build and install:
```
mvn clean install
```
