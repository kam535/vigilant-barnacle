# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.4"
gem "webrick", "~> 1.9"
gem "nokogiri"


group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-tidy"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "jekyll-sitemap", "~> 1.3"
gem "jekyll-seo-tag", "~> 2.6"
gem "kramdown-parser-gfm", "~> 1.1.0"
gem 'kramdown-math-katex'
gem 'jekyll-loading-lazy', "~> 0.1.1"


gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
