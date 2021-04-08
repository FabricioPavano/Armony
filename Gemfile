source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'rails', '~> 5.2.3'
gem 'pg', '0.20.0'
gem 'pg_search'
gem 'rack-cors'
gem 'puma', '~> 3.11'
gem 'state_machines', '~> 0.5.0'
gem 'state_machines-activerecord', "~> 0.6.0"
gem 'bootsnap', '>= 1.1.0', require: false
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'devise'
gem 'sidekiq'
gem 'sidekiq-scheduler'
gem 'acts_as_paranoid'
gem 'acts_as_list','0.9.15'
gem "logidze"
gem "auto_strip_attributes", "~> 2.6"
gem 'liquid'

gem 'painless_manufacturing',
  # path: "/Users/vic/projects/painless_manufacturing/painless_manufacturing"
  git: "https://github.com/parablesoft/painless_manufacturing.git",
  branch: "feature/crm-mods"
# ref: "a1dea6c"
# tag: "v0.1.13"

gem "mail_view", "~> 2.0.4"

gem 'stardust_rails', require: 'stardust',
  git: "https://github.com/parablesoft/stardust_rails.git",
  branch: "master"

gem 'stardust_rails-reports',
  git: "https://github.com/parablesoft/stardust_rails-reports.git",
  branch: "master",
  ref: "d6b1d0e8cea823a4117bd8e730e039207599058b"
  # path: "/Users/vic/projects/stardust/stardust_rails-reports"

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem "ffaker"
  gem "awesome_print"
  gem 'spring-commands-rspec'
  gem 'factory_bot_rails'
  gem 'wkhtmltopdf-binary-edge', '~> 0.12.5.0'
end
gem 'wicked_pdf'

group :production do
  gem 'wkhtmltopdf-binary-edge-alpine', '~> 0.12.5.0'
end

group :test do
  gem 'shoulda-matchers', require: false
  gem 'stardust-rspec',
    git: "https://github.com/parablesoft/stardust-rspec.git",
    tag: "v0.1.1"
  gem 'timecop'

end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'dotenv-rails'
end

# gem 'geocoder'
gem 'my_zipcode_gem', 
  git: "https://github.com/victornamuso/my_zipcode_gem",
  branch: "develop"

gem 'mocha', group: :test


gem 'stardust-hooks', 
  # path: "/Users/vic/projects/stardust/stardust-hooks"
  git: "https://github.com/parablesoft/stardust-hooks.git",
  branch: "feature/enhancements"
#
gem 'authorizenet'
gem 'zester'
gem 'google-protobuf', '3.9.2'
gem 'memoist', '0.16.0'
gem 'google-api-client', '~> 0.34'

gem 'carrierwave', '2.0.0.rc'
gem 'carrierwave-aws', '1.3.0'
gem 'mini_magick'


gem 'painless_manufacturing-accounting',
  # path: "/Users/vic/projects/painless_manufacturing/painless_manufacturing-accounting"
  git: "https://github.com/parablesoft/painless_manufacturing-accounting.git",
  # # tag: "v0.1.5"
  branch: "feature/vendor-sku"

gem 'stardust_rails-kpis',
  git: "https://github.com/parablesoft/stardust_rails-kpis.git",
  # tag: "v0.0.2"
  ref: "e6d171f23e8ca679e63625881fd6bdb4b699ebc1"
# branch: "master"
# path: "/Users/vic/projects/stardust/stardust_rails-kpis"
