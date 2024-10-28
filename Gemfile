# frozen_string_literal: true

source 'https://rubygems.org'

# Jekyll and theme
gem 'jekyll', '~> 4.2.0'
gem 'jekyll-theme-chirpy', '~> 7.1', '>= 7.1.1'

# For testing HTML output
group :test do
  gem 'html-proofer', '~> 5.0'
end

# Platform-specific gems for Windows and JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end

# Windows-specific gem to watch for file changes
gem 'wdm', '~> 0.1.1', platforms: [:mingw, :x64_mingw, :mswin]
