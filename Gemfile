source 'http://rubygems.org'
gemspec

gem "coveralls", "~> 0.7.0", require: false, group: :test

platforms :rbx do
  gem 'rubysl', '~> 2.0' # if using anything in the ruby standard library
  gem 'rubinius-coverage'
  gem 'rubysl-test-unit'
  gem "racc"
end
