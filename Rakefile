ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

desc "Open a Pry console"
task :console do
  Pry.start
end

# Type `rake -T` on your command line to see the available rake tasks.
