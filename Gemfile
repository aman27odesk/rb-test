require 'rbconfig'

# If you do not have OpenSSL installed, change
# the following line to use 'http://'
source 'https://rubygems.org'

ruby "2.7.2"

if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
  gem 'rb-fsevent', '<= 0.9.4'
end

# For faster file watcher updates on Windows:
gem 'wdm', '~> 0.1.0', platforms: [:mswin, :mingw]

# Windows does not come with time zone data
gem 'tzinfo-data', platforms: [:mswin, :mingw, :jruby]
gem 'slim'
# Middleman Gems
gem 'middleman', '>= 4.0.0'
gem 'middleman-sprockets'
gem 'middleman-livereload'
gem 'middleman-slim', require: false
gem 'middleman-autoprefixer'
gem 'font-awesome-middleman'
gem 'contentful_middleman' 
#, :github => 'contentful/contentful_middleman', :branch => 'dl/upgrade-to-v4'

gem 'builder'

# Google Analytics
#gem 'middleman-google-analytics'

# Assets
gem 'bootstrap-sass', '~> 3.3.6'
