# Jekyll install

## Requirements

* [Jekyll](https://jekyllrb.com/docs/installation/)
* [Rbenv](https://github.com/rbenv/rbenv)
* [Ruby](https://www.ruby-lang.org/en/documentation/installation/#apt) [2.5.1+](https://www.ruby-lang.org/en/downloads/)
* [RubyGems]( https://github.com/rubygems/rubygems)


## Install Ruby by RVM
https://rvm.io/rvm/install
```shell=
$ sudo apt update
$ sudo apt install curl g++, gcc, autoconf, automake, bison, libc6-dev, libffi-dev, libgdbm-dev, libncurses5-dev, libsqlite3-dev, libtool, libyaml-dev, make, pkg-config, sqlite3, zlib1g-dev, libgmp-dev, libreadline-dev, libssl-dev
$ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
$ curl -sSL https://get.rvm.io | bash -s stable
$ source /usr/local/rvm/scripts/rvm
$ echo "source /usr/local/rvm/scripts/rvm" >> ~/.bash_profile
$ rvm install 2.5.1
$ rvm use 2.5.1 --default
$ ruby -v
```
## Install jekll
```shell=
gem install jekyll bundler
```
## create web
```shell=
$ mkdir jekyll
$ cd jekyll
$ jekyll new myblog
$ cd myblog
$ bundle exec jekyll serve
```
* browser
![](https://i.imgur.com/h1SrOmV.png)

## create hello world file
* create file ``index.html``
```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Home</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```

## reference
http://xareelee.github.io/tech_note/2015/07/23/%E4%BD%BF%E7%94%A8-GitHub-Pages-%E5%92%8C-Jekyll-%E4%BE%86%E5%BB%BA%E7%AB%8B-Blog.html
