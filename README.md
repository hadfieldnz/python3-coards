## Synopsis

## Mark Hadfield 2018-07-05

I have now installed coards under Python 3.6 with pip, so this repository is redundant

### Mark Hadfield 2018-03-05

The coards subdirectory contains __init__.py from a Debian package downloaded from
this [link](https://packages.debian.org/buster/all/python3-coards/download]). It
purports to be a Python 3 port of the COARDS python package:

https://pypi.python.org/pypi/coards

The change log below was compiled from the change logs from the PyPi package and the
Debian package.

## Change log

### 1.0.5-3 unstable; urgency=medium

  * Fix typo in watch regex

 -- Ghislain Antony Vaillant <ghisvail@gmail.com>  Wed, 08 Mar 2017 14:51:41 +0000

### 1.0.5-2 unstable; urgency=medium

  * Switch from git-dpm to gbp
    - Drop git-dpm configuration
    - Unapply patch queue
    - Add gbp configuration
  * Fixup the VCS-Browser URI
  * Run autopkgtests for all supported Python versions

 -- Ghislain Antony Vaillant <ghisvail@gmail.com>  Tue, 28 Feb 2017 16:04:51 +0000

### 1.0.5-1 unstable; urgency=low

  * Initial release. (Closes: #849541)

 -- Ghislain Antony Vaillant <ghisvail@gmail.com>  Wed, 28 Dec 2016 13:54:39 +0000

### 1.0.5

*Release date: 20130604*

* Create converter object.

### 1.0.4

*Release date: 20130520*

* Parse microseconds.

### 1.0.3.2

*Release date: 20130218*

* Allow origin to be expressed only as HH.

### 1.0.3.1

*Release date: 20130214*

* Fix minor typo in code.

###1.0.3

*Release date: 20130214*

* Create parser/formatter objects to avoid repeated parsing.
* Happy Valentine's!

### 1.0.2

*Release date: 20120823*

* Fixed regexp that parses the origin.

### 1.0.1

*Release date: 20120818*

* Parse RFC3339 dates.

### 1.0

*Release date: 20120529*

* Refactored code so that it works with more dates.
* Using modern-package-template for directory structure.











