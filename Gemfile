# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem "faraday-retry"
gem "octokit", "~> 4.0"
gem "pry"
gem "thor"

group :test do
  gem "rspec"
  gem "simplecov", require: false
end

group :development, :test do
  gem "bixby"
end
