source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool', '2.5.0'

# 仅 Windows 本地预览需要：提供时区数据。
# 没有它，在 Windows 上运行 jekyll build/serve 会报
# "No source of timezone data could be found"。
# platforms 限制了它只在 Windows / JRuby 上安装，GitHub Pages 不受影响。
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
