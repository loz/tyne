source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem "jquery-rails"
gem 'therubyracer'

gem 'responders', :git => 'https://github.com/plataformatec/responders.git'
gem "active_model_serializers", :git => "https://github.com/josevalim/active_model_serializers.git"
gem "simple_form"
gem 'client_side_validations'
gem 'client_side_validations-simple_form'

# Tyne
gem 'tyne_ui', :git => 'https://github.com/tyne/tyne-ui.git', :branch => 'master'
gem 'tyne_core', :git => 'https://github.com/tyne/tyne-core.git', :branch => 'master'
gem 'tyne_auth', :git => 'https://github.com/tyne/tyne-auth.git', :branch => 'master'

gem 'modernizr-rails'
gem 'jquery-ui-themes'
gem 'twitter-bootstrap-rails'
gem "less-rails"

gem "i18n-js"

# Webserver
gem 'thin'

# Assets
gem "asset_sync"

group :production do
 gem 'pg'
 gem 'unicorn'
 gem 'newrelic_rpm'
 gem 'dalli'
end

# Testing
group :test, :development do
  gem 'tyne_dev', :git => 'https://github.com/tyne/tyne-dev.git', :branch => 'master'
  gem "sqlite3"
end
