source "https://rubygems.org"

# Use the github-pages gem which will install compatible versions of Jekyll and other dependencies
gem "github-pages", group: :jekyll_plugins

# Use the "minimal-mistakes-jekyll" theme
# gem "minimal-mistakes-jekyll"

# Plugins to extend Jekyll functionality
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# For Windows and JRuby users, include these gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for Windows users
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby compatibility
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
