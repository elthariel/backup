source "https://rubygems.org"

gem 'fog-openstack',
    github: 'elthariel/fog-openstack',
    branch: 'wdg'

gemspec

# Omitted from CI Environment
group :no_ci do
  gem "pry"
  gem "rb-fsevent" # Mac OS X
  gem "rb-inotify" # Linux

  gem "redcarpet"
  gem "yard"
end
