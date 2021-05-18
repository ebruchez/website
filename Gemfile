source "https://rubygems.org"

gem "jekyll-theme-chirpy"

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-xxx", "~> x.y"
  gem 'jekyll-redirect-from'
  gem 'jekyll-relative-links'
end

group :test do
  gem "html-proofer", "~> 3.19"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# # # Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# https://github.com/jekyll/jekyll/issues/8523
gem "webrick"
