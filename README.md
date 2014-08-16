gnu-trainer
===========

Script to setup emacs with consistent configuration on multiple OSes and distros.

To use you can download and run the [install file](https://raw.githubusercontent.com/Liquid-Labs/gnu-trainer/master/bin/gnu-trainer) or by copying the following line into a terminal:

```
bash <(curl -s https://raw.githubusercontent.com/Liquid-Labs/gnu-trainer/master/bin/gnu-trainer)
```

This will download and run the script on any [supported environment](#tested-environments) (generally Linux and OS X). The script will:

1) try and figure out if it can install emacs,
2) if so, install emacs,
3) output package and configuration information.

Supports emacs 23 and 24.

To Customize
------------

The current configuration used is rather simple and could use some fleshing out; feel free to suggest changes. If you want to go your own way, easy enough to fork. I considered adding a parameter to the setup script to allow it to point to alternate sources, but then figured better to keep it simple and just use git. Please do isolate and submit any general improvements to the [Liquid-Labs/gnu-trainer](https://github.com/Liquid-Labs/gnu-trainer) project.

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
