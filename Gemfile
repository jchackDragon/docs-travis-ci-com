source 'https://rubygems.org'

ruby '2.4.2' if ENV.key?('DYNO')

gem 'faraday'
gem 'html-proofer', '~> 3.0'
gem 'jekyll', '>=3.1.6'
gem 'jekyll-paginate'
gem 'jekyll-redirect-from'
gem 'puma'
gem 'pry', group: :test
gem 'rack-jekyll'
gem 'rack-ssl-enforcer'
gem 'rake'
gem 'rdiscount', '>=2.2.0.1'
gem 'rubocop', group: :test


# All of this is for Slate / middleman

gem "middleman"

# For syntax highlighting
gem "middleman-syntax"

# Plugin for middleman to generate GitHub pages
gem 'middleman-gh-pages'

# Live-reloading plugin
gem "middleman-livereload", "~> 3.3.0"

gem 'redcarpet'

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end

gem 'therubyracer', :platforms => :ruby
