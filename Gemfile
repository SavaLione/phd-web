source "https://rubygems.org"

gem "jekyll", "~> 4.3.3"


# Plugins
group :jekyll_plugins do
    gem "jekyll-feed"
    gem "jekyll-sitemap"
    gem "jekyll-seo-tag"
    gem "kramdown-parser-gfm"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]