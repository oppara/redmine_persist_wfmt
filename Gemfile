gem 'rails-render_hooks'

group :development, :test do
  gem 'rspec', '~> 2.14.0'
  gem 'rspec-rails'
  gem 'pry'
  gem 'pry-rails'
  if RUBY_VERSION >= '2.0.0'
    gem 'pry-byebug'
  else
    gem 'pry-debugger'
  end
end

group :test do
  gem 'poltergeist'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'coveralls' if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new('2.0.0')
end
