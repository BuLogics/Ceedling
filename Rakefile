#!/usr/bin/env rake
require 'bundler'
require 'rspec/core/rake_task'
require 'bundler/gem_tasks'


desc "Run all rspecs"
RSpec::Core::RakeTask.new(:spec) do |t|
  t.pattern = 'spec/**/*_spec.rb'
end

task :default => [:spec]
task :ci => [:spec]
