require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('ajaxful_rating', '2.2.8.2') do |p|
  p.description    = "Provides a simple way to add rating functionality to your application."
  p.url            = "http://github.com/kamuigt/ajaxful-rating"
  p.author         = "Edgar J. Suarez, Jack Chu"
  p.email          = "kamuigt@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }