source "https://rubygems.org"

ruby File.read('.ruby-version').strip if ENV["RACK_ENV"] == "production" # strict ruby version only on heroku

group :test do
  gem "rake"
end

# server
gem "sinatra"
gem "thin"
gem "rollbar"
gem "dalli"
gem "codeclimate-test-reporter", git: "https://github.com/grosser/ruby-test-reporter.git", ref: "grosser/merge2"
