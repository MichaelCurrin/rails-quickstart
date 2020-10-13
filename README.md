# Rails Quickstart
> Auto-generated skeleton of a Ruby on Rails app

[![Ruby 2.6](https://img.shields.io/badge/Ruby->=2.6-blue?logo=ruby&logoColor=white)](https://ruby-lang.org)
[![Rails 6](https://img.shields.io/badge/Rails-6-blue?logo=ruby-on-rails&logoColor=white)](https://rubyonrails.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)


## Preview

<div align="center">
  
![Sample screenshot](/sample.png)

</div>

<div align="center">

[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge&logo=github)](https://github.com/MichaelCurrin/rails-quickstart/generate)

</div>


## Generate a new project

If you have Rails installed globally or with Bundler, you can create a new project.

```sh
$ rails new blog
```

For resources, see my [Rails](https://github.com/MichaelCurrin/learn-to-code/tree/master/en/topics/scripting_languages/Ruby) guide.


## Installation

### Install system dependencies

Install Ruby and Bundler - see instructions in [gist](https://gist.github.com/MichaelCurrin/3af38fca4e2903cdedfb8402c18b2936).

### Clone

```sh
$ git clone git@github.com:MichaelCurrin/rails-quickstart.git
$ cd rails-quickstart
```

### Install project dependencies

```sh
$ bundle config set --local path vendor/bundle
$ bundle install
```

### Setup app

Note: I don't know what all the setup steps are - the `new` command failed and I had to remove the cache and then run webpack again - see [issue](https://github.com/Shopify/bootsnap/issues/73). The Rails 

Run `rake COMMAND` rather than `bundle exec rails COMMAND`.

```sh
rake --tasks
```

```sh
$ rake webpacker:install
$ rake db:migrate
```


## Usage

A few steps to get started. The Rails docs will be more comprehensive.

### Start dev server

```sh
$ rake server
```

Open in the browser:

- http://127.0.0.1:3000/

### Run tests

```sh
$ rake test
```


## License

Released under [MIT](/LICENSE).

This repo is mostly based on the quickstart app that comes with Rails. I've customizes with a `README.md` file.
