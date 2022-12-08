JustWhatsTheData
============

A directory of information for you to acknowledge the amount of data that web services gather from you.
This is a fork of [Just Get My Data](https://justgetmydata.com/), focusing on data collected by web services.

[![Crowdin](https://badges.crowdin.net/justwhatsthedata/localized.svg)](https://crowdin.com/project/justwhatsthedata)

## Building Locally

Just Whats The Data is built using [Jekyll](https://jekyllrb.com/) and is linted and
validated using a mixture of Ruby and Node.js packages and scripts.

**Dependencies:**

- [Ruby](https://www.ruby-lang.org) (>=2.6.6)
- [Node.js](https://nodejs.org)

**Installation**

- Clone the repository

  ```
  git clone https://github.com/justwhatsthedata/justwhatsthedata.github.io.git
  ```

- Install dependencies

  ```
  cd justwhatsthedata.github.io
  gem install bundler
  bundle install
  ```

**Building the site**

Just run `jekyll serve`

**Testing**

Tests are run via the "cibuild" script, and can be run via `./script/cibuild`

## Contributing

You can translate the main text of the page by contributing on [Crowdin](https://crowdin.com/project/justwhatsthedata)
If you want to help, do read our [contributing](CONTRIBUTING.md) guidelines.

## Misc

Search functionality modified from [DevCenter.me](https://github.com/stevestreza/DevCenter.me).

## On Media

## License

Licensed under the MIT License (MIT). See `LICENSE`.

Country Flag Icons Copyright (c) 2017 Go Squared Ltd. https://www.gosquared.com/resources/flag-icons/

DevCenter.me Copyright (c) 2013 Steve Streza

This is a detached fork of [Just Get My Data](https://justgetmydata.com/)

Created by Students of the [Complutense University of Madrid](https://www.ucm.es/) as a project for the Ethics, Legislation and Profession course. You can find more info [here](http://wikis.fdi.ucm.es/ELP/Trabajo:JustWhatsTheData).
