require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('acts_as_versioned_jw', '3.2.3') do |p|
  p.description     = "Active Record model versioning"
  p.url             = "http://github.com/jwhitehorn/acts_as_versioned"
  p.author          = "Jason Whitehorn"
  p.email           = "jason.whitehorn@gmail.com"
  p.dependencies = ['activerecord']
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
