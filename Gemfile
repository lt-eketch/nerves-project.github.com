source 'https://rubygems.org'

#http://jekyllrb.com/docs/github-pages/#deploying-jekyll-to-github-pages

require 'json'
require 'open-uri'

versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
