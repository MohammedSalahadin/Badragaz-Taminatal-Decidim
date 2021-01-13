# frozen_string_literal: true

source "https://rubygems.org"

ruby '2.6.3'

gem "decidim", "0.23.1"
# gem "decidim-consultations", "0.23.1"
# gem "decidim-initiatives", "0.23.1"
# gem "decidim-templates", "0.23.1"

gem "bootsnap", "~> 1.3"

gem "puma", ">= 4.3.5"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.9"

gem "wicked_pdf", "~> 1.4"

gem "figaro"

#gem "decidim-results"
gem "decidim-elections"
gem "decidim-templates"
gem "decidim-calendar"
#gem "decidim-navigation_maps", git: "https://github.com/Platoniq/decidim-module-navigation_maps"#old version

gem "decidim-navigation_maps", "~> 1.1.0"

gem 'decidim-navbar_links', git: "https://github.com/OpenSourcePolitics/decidim-module-navbar_links", branch: "0.23-stable"
gem 'decidim-pages'
gem 'decidim-proposals'
gem 'decidim-comments'
#gem "decidim-plans"
gem "decidim-process_groups_content_block"
gem 'decidim-accountability'
gem 'decidim-blogs'



group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri
  gem "decidim-dev", "0.23.1"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  gem "passenger"
  gem 'delayed_job_active_record'
  gem "daemons"
end

