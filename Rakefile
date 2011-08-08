require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "fcgi"
    gem.summary = %Q{FastCGI library for Ruby.}
    gem.description = %Q{FastCGI is a language independent, scalable, open extension to CGI that provides high performance without the limitations of server specific APIs. This version aims to be compatible with both 1.8x and 1.9x versions of Ruby}
    gem.email = "saksmlz@gmail.com"
    gem.homepage = "http://github.com/saks/fcgi"
    gem.authors = ["saks"]
    gem.files << "ext/fcgi/extconf.rb" << "ext/fcgi/fcgi.c" << "ext/fcgi/Makefile" << "ext/fcgi/MANIFEST"
    gem.require_paths = ["lib", "ext"]
    gem.extensions = ['ext/fcgi/extconf.rb']
    gem.extra_rdoc_files << "README.rdoc"
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end