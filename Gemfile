source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in bullet_train-billing-stripe.gemspec.
gemspec

gem "sqlite3"

gem "sprockets-rails"

# Start debugger with binding.b [https://github.com/ruby/debug]
# gem "debug", ">= 1.0.0"

# Not a direct dependency of this repo; the starter provides it.
gem "active_hash"

gem "minitest-mock"

# Match the starter host's Stripe major; 20.x is untested.
gem "stripe", "~> 19.1"

gem "standardrb", "~> 1.0"

git "https://github.com/tujucreative/bullet_train-core.git", branch: "main" do
  gem "bullet_train"
  gem "bullet_train-api"
  gem "bullet_train-incoming_webhooks"
  gem "bullet_train-integrations-stripe"
end

gem "bullet_train-billing", github: "tujucreative/bullet_train-billing", branch: "main"
