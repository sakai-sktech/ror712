# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
3.2.2
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

## Turboを理解するための準備

### 1. デフォルトのRailsアプリケーションを作成する
```shell
scaffold User name:string email:string
rails db:migrate
```

### 2. Userモデルにデータを追加する

### 3. デフォルトの`app/views/users/index.html.erb`をTurboに対応させる

### 4. デフォルトの`app/views/users/show.html.erb`をTurboに対応させる

### 5. デフォルトの`app/views/users/new.html.erb`をTurboに対応させる

### 6. デフォルトの`app/views/users/edit.html.erb`をTurboに対応させる

### 7. デフォルトの`app/views/users/_form.html.erb`をTurboに対応させる

### 8. デフォルトの`app/views/users/_user.html.erb`をTurboに対応させる





