require 'rake/testtask'
require 'yard'

# rake test
Rake::TestTask.new do |t|
  t.libs << 'test'
end

# rake yard
YARD::Rake::YardocTask.new do |t|
 t.files   = ['lib/**/*.rb']   # optional
 t.stats_options = ['--list-undoc']         # optional
end

desc "Run tests"
task :default => :test
