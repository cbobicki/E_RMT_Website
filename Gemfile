source "https://rubygems.org"

# Use GitHub Pages gem (includes jekyll and all dependencies)
gem "github-pages", group: :jekyll_plugins
# This theme comes with github-pages, but we explicitly declare it
gem "minima", "~> 2.5"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  # Add other plugins you might need:
  # gem "jekyll-seo-tag"
  # gem "jekyll-sitemap"
end

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end

# JRuby specific
platforms :jruby do
  gem "http_parser.rb", "~> 0.6.0"
end

gem "csv"