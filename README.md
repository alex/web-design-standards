# U.S. Web Design Standards

[![Build Status](https://api.travis-ci.org/18F/web-design-standards.svg?branch=18f-pages-staging)](https://travis-ci.org/18F/web-design-standards)

The [U.S. Web Design Standards](https://playbook.cio.gov/designstandards) is a library of open source UI components and a visual style guide for U.S. federal government websites.

The standards are built on the highest standards of 508 compliance, reuse best practices of existing style libraries, and follow modern web design techniques to guide us in creating beautiful and easy-to-use online experiences for the American people. Created and maintained by a team of [U.S. Digital Service](https://www.whitehouse.gov/digital/united-states-digital-service) and [18F](https://18f.gsa.gov) designers and developers, the Web Design Standards are designed for government product teams. Learn more about this project in our announcement [blog post](https://18f.gsa.gov/2015/09/28/web-design-standards/).

Design files of all the assets included on this site are available for download here: [https://github.com/18F/web-design-standards-assets](https://github.com/18F/web-design-standards-assets).

The structural setup of this repo is based off of [https://github.com/18F/pages](https://github.com/18F/pages)

### Reuse of open source style guides

Much of the guidance in Web Design Standards leans on open source designs, code, and patterns from other civic and government organizations, including:
- The Consumer Financial Protection Bureau’s [Design Manual](https://cfpb.github.io/design-manual/)
- U.S. Patent and Trademark Office’s [Design Patterns](http://uspto.github.io/designpatterns/)
- The Healthcare.gov [Style Guide](http://styleguide.healthcare.gov/)
- The UK’s Government Digital Service’s [UI Elements](http://govuk-elements.herokuapp.com/)
- Code for America’s [Chime Styleguide](https://github.com/chimecms/chime-starter)
- Pivotal Labs [Component Library](http://styleguide.cfapps.io/)

## Getting started

To begin using the U.S. Web Design Standards, include the CSS and JavaScript files in each HTML page of your project. Copy the full `_site/assets/` directory to a relevant place in your code base `cp ./_site/assets/css/main.css /path/to/your/repo/static/dir`. Add the following `<link>` and `<script>` elements in your HTML:

- `<link rel="stylesheet" href="/path/to/your/assets/css/main.css">`
- `<link rel="stylesheet" href="/path/to/your/assets/css/google-fonts.css">`
- `<script src="/path/to/your/assets/js/components.js"></script>`

## Setup for your local environment

### Requirements

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may
consider using a Ruby version manager such as
[rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to
help ensure that Ruby version upgrades don't mean all your
[gems](https://rubygems.org/) will need to be rebuilt.

On OS X, you can also use [Homebrew](http://brew.sh/) to install Ruby in
`/usr/local/bin`, which may require you to update your `$PATH` environment
variable. Here are the commands to follow to install via homebrew:

```shell
$ brew update
$ brew install ruby
```

### Installation

Now that you have verified that you have Ruby installed, clone and run the 
following [go](https://golang.org/) commands to initialize and serve the library locally.

```shell
$ git clone git@github.com:18F/web-design-standards.git
$ cd web-design-standards
$ ./go init
$ ./go serve
```

You should now be able to visit `http://127.0.0.1:4000/web-design-standards/` 
and view the web design standards locally.

Questions or need help with setup? Feel free to open an issue here [https://github.com/18F/web-design-standards/issues](https://github.com/18F/web-design-standards/issues).


### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
