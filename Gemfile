ruby File.read(".ruby-version").strip

source "https://rubygems.org"

gem "addressable"
gem "bootsnap"
gem "database_cleaner"
gem "deprecated_columns"
gem "gds-api-adapters"
gem "gds-sso"
gem "govuk-content-schema-test-helpers"
gem "govuk_app_config"
gem "govuk_sidekiq"
gem "pg"
gem "plek"
gem "rails", "5.2.0"
gem "sass-rails"
gem "uglifier"

group :development, :test do
  gem "byebug" # Comes standard with Rails
  gem "capybara"
  gem "factory_bot_rails"
  gem "govuk-lint"
  gem "poltergeist"
  gem "pry"
  gem "rspec-rails"
  gem "simplecov", require: false
  gem "simplecov-rcov", require: false
  gem "sqlite3" # Remove this when you choose a production database
  gem "timecop"
  gem "webmock", require: false
end

group :development do
  gem "listen"
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console"
end
