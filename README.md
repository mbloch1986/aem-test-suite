[![Build Status](https://img.shields.io/travis/shinesolutions/aem-test-suite.svg)](http://travis-ci.org/shinesolutions/aem-test-suite)

AEM Test Suite
--------------

AEM Test Suite is a work in progress and it's designed to be a suite of acceptance, security, performance, and recovery tests. The idea is you can run this test suite (or parts of it) against an AEM environment, as a mechanism to validate the status of that environment.

Installation
------------

* Clone Packer AEM `git clone https://github.com/shinesolutions/aem-test-suite.git`
* Install [PhantomJS](https://github.com/teampoltergeist/poltergeist/tree/v1.17.0#installing-phantomjs)
* Run `make deps` to install dependencies

Configuration
-------------

Configure the details of AEM Author, Publish, and Dispatcher in `conf.yaml` file.

Usage
-----

Run the acceptance test:

    make acceptance

Run the security test:

    make security
