# jmargutti.io
my website

## Run locally

On Windows, install Ruby with Devkit using [RubyInstaller](https://rubyinstaller.org/downloads/).

From a terminal in the repository, install Bundler and the site dependencies, then start Jekyll:

```sh
gem install bundler
bundle install
bundle exec jekyll serve
```

Open <http://127.0.0.1:4000/> in your browser. Jekyll rebuilds the site when files change; stop the server with `Ctrl+C`.
