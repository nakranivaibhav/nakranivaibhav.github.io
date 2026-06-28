source "https://rubygems.org"

# This gem bundles the exact versions of Jekyll and plugins that GitHub Pages
# runs server-side, so what you build locally matches what's deployed.
gem "github-pages", group: :jekyll_plugins

# Plugins enabled in _config.yml
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Lock http_parser.rb gem to v0.6.x on JRuby builds (platform-specific fix)
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Windows/macOS file-watching support for `jekyll serve`
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
