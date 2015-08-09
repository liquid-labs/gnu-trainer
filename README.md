gnu-trainer
===========

Script to setup emacs with consistent configuration on multiple OSes and distros.

To use you can download and run the [install file](https://raw.githubusercontent.com/Liquid-Labs/gnu-trainer/master/bin/gnu-trainer) or by copying the following line into a terminal:

```
bash <(curl -s https://raw.githubusercontent.com/Liquid-Labs/gnu-trainer/master/bin/gnu-trainer)
```

This will download and run the script on any [supported environment](#tested-environments) (generally Linux and OS X). The script will:

1. check if emacs already installed,
2. install a package manager as necessary (only on OS X),
3. install emacs if necessary and possible,
4. and configure installed emacs (support for 23 and 24+).

Supports emacs 23 and 24. As written, customizes by installing: 

* `web-mode` and
* `php-mode` packages.

Note the first time you launch emacs there will probably be a small delay as it downloads the packages. Subsequent starts will then be normal speed.

To Customize
------------

The current configuration used is rather simple and could use some fleshing out; feel free to suggest changes. The target for this configuration is general purpose web development; front, back, and everything in between.

If you want to go your own way, easy enough to fork. Please do isolate and submit any general improvements to the [Liquid-Labs/gnu-trainer](https://github.com/Liquid-Labs/gnu-trainer) project.

I considered writing the script to download the configuration in a separate step, and then allowing the source to be set on the command line. Personally, I like the idea of keeping it simple and the complication doesn't seem justified at this point.


Tested Environments
-------------------

|Environment|By|On|
|:-----|:----|----:|
|OpenSUSE 12.3|Zane Rockenbaugh|2014-08-01|
|OpenSUSE 13.1|Zane Rockenbaugh|2014-08-01|
|Amazon Linux 2012.09(*)|Zane Rockenbaugh|2014-08-01|
|OS X 10.9.4|Zane Rockenbaugh|2014-08-01|
|OS X 10.9.4 with Homebrew|Zane Rockenbaugh|2014-08-01|
|OS X 10.9.4 with MacPorts|Zane Rockenbaugh|2014-08-01|

(*) : Installs emacs 23 with standard sources.
