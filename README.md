# Hello World sample project built on Travis-CI

You can easily use Travis-CI to build your Web Applications based on Play 2.x Framework, with following steps:

 - instruct the download and setup of the release(s) of Play you want to run with in a custom script called by `before_script` in .travis.yml
 - call `path/to/play-framework/play test` with `script` definition in .travis.yml

For more general information about how to use Travis-CI, follow the guides on http://about.travis-ci.org/docs/

## Just get it work in seconds...

 - Enable Travis hook on your GitHub repository from your Travis CI profile
 - Copy `.travis.yml` and `travis/setup` from this sample project to your Play2 application
 - Publish your changes to GitHub repository and enjoy continuous integration with Travis !

# Original README 

copied from https://github.com/playframework/Play20/blob/master/samples/scala/helloworld/README

This is a very basic application that demonstrates Play 2.0 fundamentals:

 - Writing controllers and actions.
 - Routing and reverse routing.
 - Linking to public assets.
 - Using the template engine.
 - Handling forms with validation.
