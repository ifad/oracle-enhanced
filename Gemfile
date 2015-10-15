source 'http://rubygems.org'

group :development do
  gem 'jeweler', '~> 2.0'
  gem 'rspec', '~> 2.4'
  gem 'rdoc'

  git 'https://github.com/rails/rails', branch: '4-2-stable' do
    gem 'activerecord'
    gem 'activemodel'
    gem 'activesupport'
    gem 'actionpack'
    gem 'railties'
  end

  gem 'arel',           github: 'rails/arel', branch: '6-0-stable'
  gem 'journey',        github: 'rails/journey'

  gem 'activerecord-deprecated_finders'
  gem 'ruby-plsql', '>=0.5.0'

  platforms :ruby do
    gem 'ruby-oci8',    github: 'kubo/ruby-oci8'
  end
end
