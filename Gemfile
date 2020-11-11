# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby File.read(File.expand_path("../.ruby-version", __FILE__)).chomp
gem "rails", "~> 5.2.3"

gem "autoprefixer-rails", "~> 7.1", ">= 7.1.3"

gem "barnes"
gem "bootsnap", "~> 1.4", ">= 1.4.4", require: false

gem "connection_pool", "~> 2.2", ">= 2.2.1"

gem "dalli", "~> 2.7", ">= 2.7.6"

gem "failbot_rails",      "~> 0.5.0"
gem "faraday-http-cache", "~> 2.0"
gem "faraday_middleware", "~> 0.13.1"
gem "flipper",            "~> 0.10.2"
gem "flipper-redis",      "~> 0.10.2"
gem "flipper-ui",         "~> 0.10.2"

gem "geo_pattern", "~> 1.4"
gem "google-api-client", "~> 0.11"
gem "googleauth", "~> 0.8.0"

gem "jquery-datetimepicker-rails", "~> 2.4", ">= 2.4.1.0"
gem "jquery-turbolinks",           "~> 2.1"

gem "active_model_serializers", "~> 0.10.0"
gem "api-pagination", "4.7.1"
gem "kaminari", "~> 1.0", ">= 1.0.1"

gem "ims-lti", "~> 2.2.3"
gem "local_time", "~> 2.0"

gem "oauth",           "~> 0.5.4"
gem "octicons_helper", "~> 9.1.1"
gem "octokit", github: "octokit/octokit.rb"
gem "octopoller",      "~> 0.1"
gem "omniauth-github", "~> 1.3"

gem "peek",                 "~> 1.0", ">= 1.0.1"
gem "peek-dalli",           "1.2.0"
gem "peek-gc",              "~> 0.0.2"
gem "peek-git",             "~> 1.0", ">= 1.0.2"
gem "peek-performance_bar", "1.3.1"
gem "peek-pg",              "~> 1.3"
gem "peek-sidekiq",         "1.0.4"
gem "pg",                   "~> 1.1.4"
gem "pg_search",            "~> 2.2"
gem "pry-byebug",           "~> 3.7"
gem "pry-rails",            "~> 0.3.9"
gem "puma",                 "~> 4.3"

gem "rack-canonical-host", "~> 0.2.3"
gem "rack-rewrite",        "~> 1.5.0"
gem "rack-timeout",        "~> 0.5.1", require: false
gem "rails-i18n",          "~> 5.1", ">= 5.1.3"
gem "redis-namespace",     "~> 1.5", ">= 1.5.3"
gem "ruby-progressbar",    "~> 1.8", ">= 1.8.1", require: false

gem "kramdown",            "~> 2.3.0"

gem "sass-rails", "~> 5.0", ">= 5.0.6"
gem "sidekiq",    "~> 5.2", ">= 5.2.7"
gem "sprockets",  "~> 3.7", ">= 3.7.2"

gem "turbolinks", "~> 2.5", ">= 2.5.4"
gem "typhoeus",   "~> 1.3"

gem "uglifier",      "~> 4.1"
gem "unicode-emoji", "~> 1.1"

group :development do
  gem "web-console", "~> 3.5", ">= 3.5.1"
end

group :development, :test do
  gem "awesome_print",            "~> 1.8", require: "ap"
  gem "bullet",                   "~> 6.0.1"
  gem "dotenv-rails",             "~> 2.7.4"
  gem "fuubar",                   "~> 2.4.0"
  gem "guard-rspec",              "~> 4.7", ">= 4.7.3", require: false
  gem "knapsack",                 "~> 1.14", ">= 1.14.1"
  gem "rails-controller-testing", "~> 1.0", ">= 1.0.4"
  gem "rspec-rails",              "~> 3.6", ">= 3.6.1"
  gem "rubocop",                  "~> 0.49.1", require: false
  gem "scss_lint",                "~> 0.54.0", require: false
  gem "spring",                   "~> 2.1", ">= 2.1.0"
  gem "spring-watcher-listen",    "~> 2.0", ">= 2.0.1"
  gem "terminal-notifier-guard",  "~> 1.7"
  gem "timecop",                  "~> 0.9.1"
end

group :production do
  gem "dogstatsd-ruby",     "~> 4.5"
  gem "lograge",            "~> 0.11.2"
  gem "newrelic_rpm",       "~> 6.5", ">= 6.5.0.357"
  gem "pinglish",           "~> 0.2.1"
  gem "puma_worker_killer", "~> 0.1.1"
  gem "rack-tracker",       "~> 1.11.1"
end

group :test do
  gem "action-cable-testing", "~> 0.3"
  gem "database_cleaner",     "~> 1.6", ">= 1.6.1"
  gem "factory_bot_rails",    "~> 4.8"
  gem "faker",                "~> 1.8", ">= 1.8.4"
  gem "shoulda-matchers",     "4.0.0.rc1"
  gem "simplecov",            "~> 0.15.0", require: false
  gem "vcr",                  "~> 3.0", ">= 3.0.3"
  gem "webmock",              "~> 3.5"
end
