source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

# ruby 2.1.1 not building locally on OS X due to a bug, overriding github
# ruby versions['ruby']

ruby '2.1.7'

gem 'github-pages', versions['github-pages']

