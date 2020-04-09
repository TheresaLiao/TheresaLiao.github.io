# Jekyll install

## Requirements

* [Jekyll](https://jekyllrb.com/docs/installation/)
* [Rbenv](https://github.com/rbenv/rbenv)
* [Ruby](https://www.ruby-lang.org/en/documentation/installation/#apt) [2.5.1+](https://www.ruby-lang.org/en/downloads/)
* [RubyGems]( https://github.com/rubygems/rubygems)

```shell=
$ tar -zxf ruby-2.5.8.tar.gz
$ cd ruby-2.5.8.tar
$ ./configure --prefix=/usr
$ make
```


```shell=
## Ruby
$ sudo apt-get install ruby-full
## RubyGems
$ gem install nokogiri
$ gem install jekyll bundler

$ sudo apt-get install ruby-full build-essential zlib1g-dev
$ echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
$ echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
$ echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
$ source ~/.bashrc

$ gem install jekyll bundler

$ cd ${PROJECT}
$ jekyll new myblog
$ cd myblog
$ bundle exec jekyll serve
```

![](https://i.imgur.com/ah3MJsN.png)

## reference
http://xareelee.github.io/tech_note/2015/07/23/%E4%BD%BF%E7%94%A8-GitHub-Pages-%E5%92%8C-Jekyll-%E4%BE%86%E5%BB%BA%E7%AB%8B-Blog.html
