# Process to build a jekyll site

## Installation

- Install ruby:

`sudo apt-get install ruby-full build-essential zlib1g-dev`

- Set environment variables

` code
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

`

- Finally install jekyll and blunder
  
  `gem install jekyll bundler`

## Fork repo with your desired themes:

Search for themes for your site on following sites and fork the desired one on your github.

- jamstackthemes.dev
- jekyllthemes.org
- jekyllthemes.io
- jekyll-themes.com

## Rename forked github repo

Rename the repo from setting to : {git_username}.github.io

For example: In our case we have data_weavers.github.io

Note: git_username can be either github username or organization name.

## Install repo locally and run following command to view site:
 
- Install missing packages
`bundle install`

- View the site locally
  `bundle exec jekyll serve`

## Make changes in _config.yml file for github url

## Make other changes in _data file and provide data according to your required needs.