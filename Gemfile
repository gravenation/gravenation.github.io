source "https://rubygems.org"

gem "jekyll", "~> 4.4.1"
gem "minimal-mistakes-jekyll", :github => "mmistakes/minimal-mistakes"
gem "webrick", "~> 1.9"



group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-include-cache"
  gem "jekyll-archives"
end

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:windows, :jruby]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:windows, :jruby]
