source "https://rubygems.org"
gem 'spec', '~> 5.3', '>= 5.3.4'
gem 'minimal-mistakes-jekyll', '~> 4.15', '>= 4.15.1'

gem 'github-pages', group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
  gem 'jekyll-gist'
  gem 'jekyll-feed'
  gem 'jemoji'
  gem 'jekyll-algolia'
  gem 'jekyll-include-cache', '~> 0.1.0'
end


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
