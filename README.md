This is a fork of the jekyll-gitbook theme, for the documentation of the JARVIS 3D Motion Capture Toolbox.

## Instructions for running jekyll locally:

- nstall ruby with <code>sudo apt install ruby</code>
- install other dependencies with <code>sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev</code>
- make ruby install stuff locally with
  ~~~
      echo 'export GEM_HOME=~/.ruby/' >> ~/.bashrc
      echo 'export PATH="$PATH:~/.ruby/bin"' >> ~/.bashrc
      source ~/.bashrc
  ~~~
- install bundler with <code>gem install bundler</code>
- install other gems with <code>bundle install</code>
- launch jekyll locally with <code>bundle exec jekyll serve</code>
