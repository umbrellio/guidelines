# UMBRELLIO guidelines

This manual describes the style and minimal requirements of maintaining and supporting the UMBRELLIO's github repositories.

## Table of contents:

* [Github Repository Design](#github-repository-design)
  * Own projects
    * [Title](#title)
    * [Description](#description)
    * [Table of contents](#table-of-contents)
    * [Links](#links-in-development)
    * [Contributing / Code of Conduct](#contributing-code-of-conduct)
    * [License / Copyright / About us](#license-copyright-about-us)
  * [Forks](#forks)
* [External services (CI and others)](#external-services)
* [Code style and Workflow design](#code-style-and-workflow-design)
  * [Workflow Design](#workflow-design-in-development)
  * [Code of Conduct and Contributing](#code-of-conduct-and-contributing-rules)
  * [Versioning](#versioning)
  * [Changelog](#changelog)
* [Full Example](#full-example)

## Github Repositry Design

### Title

Minimal description of the repository. Should describe the main objective of the project. Clear and correct formuatlion is needed because it affects the SEO part.

### Description

An introductory description into the project with the necessary information required to quickly understand the main objective of the project.
Should contain:
- logo (optional);
- minimal project statistics in the form of badge blocks that will provide an information about:
  - current project version;
  - current build status;
  - current test coverage;
- text of description.

### Table of contents

The main section with project documentation in an arbitary form (can be moved to the wiki section of the github repository). Basic form:
- Part 1. Requirements
  - Minimal project requrements such as platform, operating system, native dependencies and etc.
- Part 2. Installation
  - Detailed instructions for installing the project and some specific notes.
- Part 3. Usage
  - The main documentation section. Arbitary form. Can be placed in the wiki section of the repository (or some of them with symlinks).

### Links

Links to arcticles that refers to the current project (articles of other companies, our articles, Medium links, reddit topics and etc).
For the high popular projects this section is optional.

### Contributing / Code of Conduct

Provide a link to our [Contributing Rules](https://github.com/umbrellio/guidelines/blob/master/CONTRIBUTING.md)

Provide a link to our [Code of Conduct](https://github.com/umbrellio/guidelines/blob/master/CODE_OF_CONDUCT.md)

### License / Copyright / About Us

Main sections:
- License: short description, license type, link to the license file;
- About us: briefly shows the company ideals and the list of the project maintainers and top contributors.
  Basic form:
  - (reuired) [company logo with sponsorship label](https://github.com/umbrellio/Umbrellio);
  - (optional) short description that describes companie's values;
  - (required) short list of top maintainers and contributors.

## Forks

Fork should have a changed readme: a small CHANGES section should be placed in the top of the readme file.
This section briefly describes the changes made to the project: purpose, reasons and functionality.

## External services

Each repository should correspond to the modern standards and requirements of the development processes which followed by the company in a given moment. Our requirements are: full test coverage, full compliance with code style standarts and a successful build of othe project.
These requirements can be achieved via:

- [HoundCI](https://houndci.com/) (code style and code review)
  - [Documentation](https://houndci.com/configuration);
  - [rubocop integration](https://houndci.com/configuration#ruby);
  - [eslint integration](https://houndci.com/configuration#eslint);
  - [sass-lint integration](https://houndci.com/configuration#sass-lint);
- [CoverAlls](https://coveralls.io/) (test coverage)
  - [Documentation](https://docs.coveralls.io);
  - [Ruby integration](https://docs.coveralls.io/ruby-on-rails);
  - [JavaScript integration](https://docs.coveralls.io/javascript);
- [TravisCI](https://travis-ci.org/) (build and test)
  - [Introduction](https://docs.travis-ci.com/user/for-beginners/);
  - [Ruby integration](https://docs.travis-ci.com/user/languages/ruby/);
  - [JavaScript integration](https://docs.travis-ci.com/user/languages/javascript-with-nodejs/);

## Code style and Workflow design

### Workflow Design

The style of development is highly individual for each project. Workflow design should be chosen depending on the popularity and size of the project.

Use [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) for the big and popular project and typical PR-approach for the small project.

### Code of Conduct and Contributing rules

- Our [Code of Conduct](https://github.com/umbrellio/guidelines/blob/master/CODE_OF_CONDUCT.md);
- Our [Contributing Rules](https://github.com/umbrellio/guidelines/blob/master/CONTRIBUTING.md);

### Versioning

Follow [Semver 2.0.0](https://semver.org) standard.
- [npm semver tutorial](https://docs.npmjs.com/getting-started/semantic-versioning)
- [ruby-gems semver tutorial](http://guides.rubygems.org/patterns/#semantic-versioning)

### Changelog

It is necessary to have `CHANGELOG.md` file where you can always find out and see what changes have been made to each version of the project.

Follow [KeepChangelog 1.0.0](http://keepachangelog.com/en/1.0.0/) standard.

## Full Example

(In active development)
