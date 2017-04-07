# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.
require 'rubygems'
require_relative 'config/application'
require 'ci/reporter/rake/rspec'

gem 'ci_reporter'
require 'ci/reporter/rake/test_unit' # use this if you're using Test::Unit

Rails.application.load_tasks
task :rspec => 'ci:setup:rspec'