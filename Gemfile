# frozen_string_literal: true

source "https://rubygems.org"

ruby "3.2.2"  # (or 3.1.3 if you prefer; both work on Netlify)

# Core site generator
gem "jekyll", "~> 4.3"

# Required for Ruby 3+
gem "webrick", "~> 1.8"

# Common Jekyll plugins
gem "jekyll-feed", "~> 0.17"
gem "jekyll-sitemap", "~> 1.4"

# If you use Beautiful Jekyll as a remote theme:
gem "jekyll-remote-theme", "~> 0.4"


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
  
gemspec

