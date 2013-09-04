source :rubygems

gemspec

group :guard do
  gem 'guard-rspec'
  gem 'rb-fsevent'
  gem 'growl'
end

if File.directory?(File.expand_path("../../riak-client", __FILE__))
  gem 'riak-client', :git => 'git@github.com:jacepp/riak-ruby-client.git', :branch => 'version-trim'
end

platforms :jruby do
  gem 'jruby-openssl'
end
