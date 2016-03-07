# ${artifactId}

[![Build Status](https://travis-ci.org/stefanbirkner/${artifactId}.svg?branch=master)](https://travis-ci.org/stefanbirkner/${artifactId})

${artifactId} is published under the
[MIT license](http://opensource.org/licenses/MIT). It uses Java 8. Please
[open an issue](https://github.com/stefanbirkner/${artifactId}/issues/new)
if you want to use it with an older version of Java.


## Installation

${artifactId} is available from
[Maven Central](http://search.maven.org/).

    <dependency>
      <groupId>${groupId}</groupId>
      <artifactId>${artifactId}</artifactId>
      <version>${version}</version>
    </dependency>


## Usage

...


## Contributing

You have three options if you have a feature request, found a bug or
simply have a question about ${artifactId}.

* [Write an issue.](https://github.com/stefanbirkner/${artifactId}/issues/new)
* Create a pull request. (See [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/index.html))
* [Write a mail to mail@stefan-birkner.de](mailto:mail@stefan-birkner.de)

## Development Guide

${artifactId} is build with [Maven](http://maven.apache.org/). If you
want to contribute code than

* Please write a test for your change.
* Ensure that you didn't break the build by running `mvn test`.
* Fork the repo and create a pull request. (See [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/index.html))

The basic coding style is described in the
[EditorConfig](http://editorconfig.org/) file `.editorconfig`.

${artifactId} supports [Travis CI](https://travis-ci.org/) for continuous
integration. Your pull request will be automatically build by Travis
CI.


## Release Guide

* Select a new version according to the
  [Semantic Versioning 2.0.0 Standard](http://semver.org/).
* Set the new version in `pom.xml` and in the `Installation` section of
  this readme.
* Commit the modified `pom.xml` and `README.md`.
* Run `mvn clean deploy` with JDK 8.
* Add a tag for the release: `git tag ${artifactId}-X.X.X`
