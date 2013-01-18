# Sample project to demonstrate Travis CI and Play 2 in action

You can easily use [Travis CI](https://travis-ci.org) to build your Web Applications based on Play 2.x Framework, with following steps:

 - instruct the download and setup of the release(s) of Play you want to run with in a custom script called by `before_script` in .travis.yml
 - call `path/to/play-framework/play test` with `script` definition in .travis.yml

For more general information about how to use Travis-CI, follow the guides on http://about.travis-ci.org/docs/

## Just get it work in seconds...

 - Enable Travis hook on your GitHub repository from your Travis CI profile
 - Copy `.travis.yml` from this sample project to your Play2 application, and update it to refer to required version(s) of Play 2.x
 - Configure the database dependency. The example here uses PostgreSQL, see related changes in commit 418d65d06f64aef15e114e87c64584a82a103069
 - Publish your changes to GitHub repository and enjoy continuous integration with Travis !
 - Show the build status in your README.md: [![Build Status](https://travis-ci.org/gildegoma/travis-ci-ScalaOnPlay-sample.png?branch=database-integration)](https://travis-ci.org/gildegoma/travis-ci-ScalaOnPlay-sample)

# Original README from Computer-Database sample

copied from https://github.com/playframework/Play20/blob/master/samples/scala/computer-database/README

This is a classic CRUD application, backed by a JDBC database. It demonstrates:

- Accessing a JDBC database, using Anorm.
- Achieving, table pagination and CRUD forms.
- Integrating with a CSS framework (Twitter Bootstrap ).

Twitter Bootstrap requires a different form layout to the default one that the Play 2.0 form helper generates, so this application also provides an example of integrating a custom form input constructor.
