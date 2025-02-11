source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.3"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem "rails", "~> 6.0.3", ">= 6.0.3.7"
# Use mysql as the database for Active Record
gem "mysql2", ">= 0.4.4"
# Use Puma as the app server
gem "puma", "~> 4.1"
# Use SCSS for stylesheets
gem "sass-rails", ">= 6"
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem "webpacker", "~> 4.0"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "jbuilder", "~> 2.7"
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.2", require: false

# アセット
gem "bulma-rails"
gem "bulma-extensions-rails"
gem "carrierwave"
gem "carrierwave-base64"
gem "mini_magick"

# 認証
gem "sorcery"

# UI/UX
gem "rails-i18n"

# ページネーション
gem "pagy", "~> 5.6"

# 検索
gem "ransack"

# モデル
gem "enum_help"
gem "active_model_serializers"

# SEO
gem "meta-tags"
gem "sitemap_generator"

# 環境毎の定数管理
gem "config"

# 外部ストレージ設定
gem "fog-aws"

group :development, :test do
  # デバッグ
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "pry-rails"
  gem "pry-byebug"
  gem "pry-doc"
  # テスト
  gem "rspec-rails"
  gem "factory_bot_rails"
  # ダミーデータ
  gem "faker"
  # メール
  gem "letter_opener_web"
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.2"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  # Lintチェック
  gem "rubocop", require: false
  gem "rubocop-rails", require: false
  gem "rails_best_practices"
  # エラー画面のカスタマイズ、ブラウザ上でirbを使えるようにする
  gem "better_errors" # render better error page
  gem "binding_of_caller" # use irb on better_errors
  # N+1の検知
  gem "bullet"
end

group :test do
  # ブラウザ操作シュミレーター
  gem "capybara"
  # Chromeとやりとりするインターフェース
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
