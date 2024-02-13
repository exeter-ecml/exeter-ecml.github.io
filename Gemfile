source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.9.5"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "jekyll-theme-hydeout", "~> 4.2"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "github-pages", "~> 230"
  gem "jekyll-feed", "~> 0.17.0"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
gem "nokogiri", ">= 1.13.7"
gem "webrick"

gem "faraday-retry", "~> 2.2"
