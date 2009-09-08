require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('ajaxful_rating', '2.1.2') do |p|
  p.description    = "Provides a simple way to add rating functionality to your application."
  p.url            = "http://github.com/edgarjs/ajaxful-rating"
  p.author         = "Edgar J. Suarez"
  p.email          = "e@dgar.org"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
