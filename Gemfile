source 'https://rubygems.org'

gemspec

gem 'sqlite3'

version = ENV["RAILS_VERSION"] || "6.0.3.7"
rails = case version
        when "master"
          {:github => "rails/rails"}
        else
          "~> #{version}"
        end
gem "rails", rails

if version < "4"
  gem "minitest", "~> 4.7.5"
end
