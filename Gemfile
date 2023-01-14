source "https://rubygems.org"
gem "minima", "~> 2.5"

# gem "jekyll", "~> 4.3.1"

# gem "github-pages", group: :jekyll_plugins
gem "github-pages", "~> 227", group: :jekyll_plugins
group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.12"
end


# gem "tzinfo-data"
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
end

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
    gem "jekyll-paginate"
    gem "jekyll-sitemap"
    gem "jekyll-include-cache"
    gem "jekyll-algolia"
end

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.7"
