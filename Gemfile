source :rubygems

group :development do
  gem "jeweler", '~> 1.8.3'
end

group :test do
  gem "rspec", "~> 2.10.0"
  gem "session", "~> 2.4.0"
  gem "diff-lcs", "~> 1.1.2"
  if RUBY_VERSION.include?("1.9")
    gem "ruby-debug19", "~> 0.11.6"
  else
    gem "ruby-debug", "~> 0.10.4"
  end
end
