# frozen_string_literal: true
require "rubygems"
require "bundler/setup"

desc "Deploy to nomoon.github.io(master)"
task :deploy do
  ARGV.replace ["--url", "git@github.com:nomoon/nomoon.github.io.git", "--branch", "--master"]
  load Gem.bin_path("mgd", "mgd")
end

desc "Run development server"
task :server do
  ARGV.replace ["server"]
  load Gem.bin_path("middleman", "middleman")
end

task default: :server
