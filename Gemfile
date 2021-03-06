# frozen_string_literal: true

source "https://rubygems.org"

ruby "2.4.2"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "5.1.4"

gem "aasm"
gem "action_args"
gem "active_link_to"
gem "activerecord-session_store"
gem "acts_as_list"
gem "amazon-ecs"
gem "annotate"
gem "autoprefixer-rails"
# Use aws-sdk 2.x for Paperclip
# https://github.com/thoughtbot/paperclip/issues/2484
gem "aws-sdk", "< 3.0"
gem "bootsnap", require: false
gem "bootstrap"
gem "bourbon"
gem "browser"
gem "by_star"
gem "commonmarker"
gem "counter_culture"
gem "dalli"
gem "delayed_job"
gem "delayed_job_active_record"
gem "devise"
gem "discord-notifier"
gem "doorkeeper"
gem "draper"
gem "email_validator"
gem "enumerize"
gem "figaro"
gem "flutie"
gem "font-awesome-sass"
gem "github-markup"
gem "gon"
gem "graphql"
gem "graphql-batch"
gem "gretel"
gem "groupdate"
gem "hashdiff"
gem "http_accept_language"
gem "httparty"
gem "imgix-rails"
gem "impressionist"
gem "jb"
gem "jquery-rails"
gem "kaminari"
gem "keen"
gem "koala"
gem "meta-tags"
gem "mini_magick"
gem "miro"
gem "mjml-rails"
gem "moji"
gem "nokogiri"
gem "omniauth-facebook"
# 1.4系だとFacebookのOAuth周りでおかしくなるので1.3系を使う
# https://github.com/intridea/omniauth-oauth2/issues/81
gem "omniauth-oauth2", "~> 1.3.1"
gem "omniauth-twitter"
gem "paperclip"
gem "pg"
gem "puma"
gem "puma_worker_killer"
gem "pundit"
gem "rack-cors", require: "rack/cors"
gem "rack-rewrite"
gem "rails-html-sanitizer"
gem "rails-i18n"
gem "rails_autolink"
gem "ransack"
gem "rmagick"
# To use font-awesome-sass
# https://github.com/sass/sassc-rails/issues/6
gem "sass-rails", require: false
gem "sassc-rails"
gem "sitemap_generator"
gem "slack-notifier"
gem "slim"
gem "traceroute"
gem "twitter"
gem "uglifier"
gem "validate_url"
gem "virtus"
gem "webpacker"

group :development, :test do
  gem "awesome_print"
  gem "dmmyix"
  gem "pry"
  gem "pry-alias"
  gem "pry-byebug"
  gem "pry-coolline"
  gem "pry-rails"
  gem "rspec-mocks"
  gem "rspec-rails"
end

group :development do
  gem "active_record_query_trace"
  gem "better_errors"
  gem "binding_of_caller" # Using better_errors
  gem "bullet"
  gem "derailed_benchmarks"
  gem "graphiql-rails"
  gem "i18n-tasks"
  gem "letter_opener_web"
  gem "listen" # Rails 5から `rails s` するときに必要になった
  gem "rubocop"
  gem "ruby_identicon"
  gem "scss_lint", require: false
  gem "spring"
  gem "spring-commands-rspec", require: false
  gem "stackprof"
  gem "thin"
end

group :test do
  gem "capybara"
  gem "coveralls", require: false
  gem "database_rewinder"
  gem "factory_bot_rails"
  gem "poltergeist"
  gem "timecop"
end

group :production do
  gem "bugsnag"
  gem "heroku-deflater"
  gem "lograge"
end
