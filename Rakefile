# frozen_string_literal: true
require "rubygems"
require "bundler/setup"

require "middleman-gh-pages"
ENV["BRANCH_NAME"] = "master"

desc "Run development server"
task :server do
  ARGV.replace ["server"]
  load Gem.bin_path("middleman", "middleman")
end

task default: :server
