source 'https://rubygems.org'

gem 'jruby-openssl', :platforms => :jruby
gem 'rake'
gem 'yard'

group :development do
  gem 'growl'
  platforms :ruby_19, :ruby_20 do
    gem 'guard'
    gem 'guard-bundler'
    gem 'guard-rspec'
  end
  gem 'kramdown'
  gem 'plymouth', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'pry'
  gem 'pry-debugger', :platforms => [:mri_19, :mri_20, :mri_21]
  gem 'rb-fsevent'
end

group :test do
  gem 'coveralls', :require => false
  gem 'json', '>= 1.8.1', :platforms => [:jruby, :ruby_18, :ruby_19]
  gem 'mime-types', '~> 1.25', :platforms => [:jruby, :ruby_18]
  gem 'rack-test'
  gem 'rspec', '>= 2.14'
  gem 'rubocop', '>= 0.19', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'simplecov', :require => false
end

gemspec
