[![GitHub version](https://badge.fury.io/gh/yunfuliu%2Fpixkit.png)](http://badge.fury.io/gh/yunfuliu%2Fpixkit)

pixkit
======
For only academic usages of image processing (`pixkit-image`) and machine learning (`pixkit-ml`).

Contains image processing and machine learning related methods which <b>had been published</b> (on articles, e.g., journal or conference papers). 
In addition to above implementations, some frequently utilized tools, i.e., attack simulation and quality assessment, are also involved as expected.

The repo, OpenCV, is used to build up all the pixkit functions: <https://github.com/Itseez/opencv>

Functions
---------
By far, the current version, `/modules/pixkit-image` involves the following function groups:

** **attack**: Usually used to simulate attack for "watermarking".

** **comp**: Image compression.

** **filtering**: Image filtering.

** **edgedetection**: Edge detection.

** **halftoning**: Image halftoning. Turn images into binary (halftone) form.

** **enhancement::local**: Image contrast enhancement methods, regional methods.

** **enhancement::global**: Image contrast enhancement methods, global methods.

** **qualityassessment**: Image quality assessment.

Also, `/modules/pixkit-ml` involves the following function groups:

** **clustering**: Data clustering.

** **labeling**: Image labeling.

For users
---------
See [manual](https://github.com/yunfuliu/pixkit/blob/master/MANUAL.md) for details.

For contributors
----------------
Please read [CONTRIBUTING.md](https://github.com/yunfuliu/pixkit/blob/master/CONTRIBUTING.md) in this directory.  
Many thanks to our [contributors](https://github.com/yunfuliu/pixkit/graphs/contributors).

Bugs
----
Please "report bugs on GitHub <https://github.com/yunfuliu/pixkit/issues>".

License
-------
Please read [LICENSE.txt](https://github.com/yunfuliu/pixkit/blob/master/LICENSE.txt) in this directory.

Others
------
[Semantic Versioning](http://semver.org/) is used in our version control.
