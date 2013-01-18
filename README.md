# Sample project to demonstrate Travis CI and Play 2 in action

You can easily use [Travis CI](https://travis-ci.org) to build your Web Applications based on Play 2.x Framework, with following steps:

 - instruct the download and setup of the release(s) of Play you want to run with in a custom script called by `before_script` in .travis.yml
 - call `path/to/play-framework/play test` with `script` definition in .travis.yml

For more general information about how to use Travis-CI, follow the guides on http://about.travis-ci.org/docs/

## Just get it work in seconds...

 - Enable Travis hook on your GitHub repository from your Travis CI profile
 - Copy `.travis.yml` from this sample project to your Play2 application, and update it to refer to required version(s) of Play 2.x, maybe start a database service for your tests,...
 - Publish your changes to GitHub repository and enjoy continuous integration with Travis !
 - Show the build status in your README.md: [![Build Status](https://travis-ci.org/gildegoma/travis-ci-ScalaOnPlay-sample.png?branch=master)](https://travis-ci.org/gildegoma/travis-ci-ScalaOnPlay-sample)

# Original README from Hello World sample

copied from https://github.com/playframework/Play20/blob/master/samples/scala/helloworld/README

This is a very basic application that demonstrates Play 2.0 fundamentals:

 - Writing controllers and actions.
 - Routing and reverse routing.
 - Linking to public assets.
 - Using the template engine.
 - Handling forms with validation.
