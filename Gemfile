source "https://rubygems.org"

gem "rails", "5.2.0"
gem "bootsnap"

gem "database_cleaner"
gem "deprecated_columns"
group :development, :test do
  gem "sqlite3" # Remove this when you choose a production database
  gem "factory_bot_rails"
  gem "timecop"
  gem "webmock", require: false
  gem "rspec-rails"
  gem "byebug" # Comes standard with Rails
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console"
  gem "listen"
end
