source "https://rubygems.org"
# Hello! This is the default Gemfile for new Jekyll apps. You may wish to add
# additional gems in this file. However, note that this must be a valid YAML list.
#
# Each entry below is a gem request; you can set the version constraint for each
# gem by using a version specifier.  For more info on gem version specifiers, see:
# https://guides.rubygems.org/gemspec/#version-specification
#
# The default setup uses the github-pages gem to provide the same gems GitHub
# uses to build GitHub Pages. To have the same versions as GitHub Pages, run:
# `bundle` and `bundle lock --add-platform ruby x86_64-win32`

gem "jekyll", "~> 4.3.0"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"

# Required for Ruby 3.4+
gem "csv"
gem "base64"

# If you want to use GitHub Pages, uncomment the line below.
# To upgrade, run `bundle update github-pages` or just `bundle update` and it will
# attempt to upgrade all gems in your Gemfile to the latest versions.
# gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-sitemap", "~> 1.4"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` to `v0.6.x` on JRuby builds since newer versions of this gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
