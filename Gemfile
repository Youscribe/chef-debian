source 'https://rubygems.org/'

chef_version = []
unless ENV['CHEF_VERSION'].to_s.empty?
  chef_version = Gem::Requirement.new(ENV['CHEF_VERSION'])
end

gem 'rake'
gem 'chef', chef_version

group :test do
  gem 'foodcritic', '~> 1.7'
end
