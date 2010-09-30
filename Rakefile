require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('ajaxful_rating_jquery', '2.2.8.2') do |p|
  p.description    = "Provides a simple way to add rating functionality to your application. This version works with jQuery instead of prototype and uses unobtrusive javascript."
  p.url            = "http://github.com/kamui/ajaxful-rating"
  p.author         = "Jack Chu, Edgar J. Suarez"
  p.email          = "kamuigt@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }