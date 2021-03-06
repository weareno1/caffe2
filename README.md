## Installation
### dependence
0. almost all dependence are installed in /usr/local/; contact OP if some packages misssing
1. `sudo yum install cmake3`

### clone & install 
1. `clone this repo` to CAFFE_ROOT_DIR
2. `cd caffe2`
3. `make -j16` 
4. `python -c 'import sys; sys.path.insert(0, "CAFFE_ROOT_DIR/build"); import caffe2 as c2; print c2.__file__'`

## merge caffe2/caffe (if necessary)
1. `git check out master`
2. `git pull https://github.com/caffe2/caffe2.git master`
3. `resolve conflict`
4. `git push origin master`


# Caffe2

[![License](https://img.shields.io/badge/License-Apache%202.0-brightgreen.svg)](https://opensource.org/licenses/Apache-2.0)
[![TravisCI Build Status](https://img.shields.io/travis/caffe2/caffe2.svg)](https://travis-ci.org/caffe2/caffe2)
[![Appveyor Build Status](https://img.shields.io/appveyor/ci/Yangqing/caffe2.svg)](https://ci.appveyor.com/project/Yangqing/caffe2)

Caffe2 is a lightweight, modular, and scalable deep learning framework. Building on the original [Caffe](http://caffe.berkeleyvision.org), Caffe2 is designed with expression, speed, and modularity in mind.

## News and Events

[Caffe2 research award competition request for proposals](https://research.fb.com/programs/research-awards/proposals/caffe2-rfp/)

## Questions and Feedback

Please use Github issues (https://github.com/caffe2/caffe2/issues) to ask questions, report bugs, and request new features.

Please participate in our survey (https://www.surveymonkey.com/r/caffe2). We will send you information about new releases and special developer events/webinars.


## License

Caffe2 is released under the [Apache 2.0 license](https://github.com/caffe2/caffe2/blob/master/LICENSE). See the [NOTICE](https://github.com/caffe2/caffe2/blob/master/NOTICE) file for details.

### Further Resources on [Caffe2.ai](http://caffe2.ai)

* [Installation](http://caffe2.ai/docs/getting-started.html)
* [Learn More](http://caffe2.ai/docs/learn-more.html)
* [Upgrading to Caffe2](http://caffe2.ai/docs/caffe-migration.html)
* [Datasets](http://caffe2.ai/docs/datasets.html)
* [Model Zoo](http://caffe2.ai/docs/zoo.html)
* [Tutorials](http://caffe2.ai/docs/tutorials.html)
* [Operators Catalogue](http://caffe2.ai/docs/operators-catalogue.html)
* [C++ API](http://caffe2.ai/doxygen-c/html/classes.html)
* [Python API](http://caffe2.ai/doxygen-python/html/namespaces.html)
