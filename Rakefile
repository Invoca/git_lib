#!/usr/bin/env rake
# frozen_string_literal: true

require 'rspec/core/rake_task'
require 'rubocop/rake_task'
require 'coveralls/rake/task'
require "bundler/gem_tasks"
require 'bundler/audit/task'

RSpec::Core::RakeTask.new(:spec)
RuboCop::RakeTask.new
Coveralls::RakeTask.new
Bundler::Audit::Task.new

task test: :spec
task rspec: :spec
task default: :spec
