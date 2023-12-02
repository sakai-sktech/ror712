# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## デフォルトで`rails new`した時にインストールされるgem
```ruby
rails new default712
```
gem "rails", "~> 7.1.2"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem "debug", platforms: %i[ mri windows ]
gem "web-console"
gem "capybara"
gem "selenium-webdriver"


### オプションで`jbuilder`を除外指定した場合。`jbuilder`以外のgemは同じ
```ruby
rails new default712skip5 --skip-action-cable --skip-action-text --skip-action-mailer --skip-action-mailbox --skip-jbuilder
```
