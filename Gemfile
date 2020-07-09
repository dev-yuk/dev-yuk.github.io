source "https://rubygems.org"

# Jekyll itself is supplied by the "github-pages" gem listed below. 
# Don't ask me why.
# gem "jekyll", "~> 4.1.0"

group :jekyll_plugins do
  gem "github-pages"
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-timeago", "~> 0.13"
end

platforms :mingw, :x64_mingw, :mswin do
  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  # and associated library. Also, its slow at watching directories apparently.. 
  # so fix that too ... 
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1.1"
end
