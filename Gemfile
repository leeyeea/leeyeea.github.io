source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

# 禁用 wdm（装不上的废弃插件）
# gem "wdm", "~> 0.1.0" if Gem.win_platform?

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "hawkins"
end

# ✅ 固定时区错误（Windows 必须加）
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]