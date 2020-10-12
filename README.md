# Rails Quickstart
> Auto-generated skeleton of a Ruby on Rails app

Made with: Ruby, Rails, Yarn


## Preview

<div align="center">
  
![Sample screenshot](/sample.png)

</div>


## Generate a new project

If you have Rails installed globally or with Bundler, you can create a new project.

```sh
$ rails new blog
```


## Resources

- Ruby on Rails Guides - https://guides.rubyonrails.org/
- Getting Started with Rails - https://guides.rubyonrails.org/getting_started.html


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

