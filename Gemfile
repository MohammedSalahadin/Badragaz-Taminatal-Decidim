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

gem "decidim-core"
gem "decidim-admin"
gem "decidim-system"
gem "decidim-api"
gem "decidim-comments"
gem "decidim-proposals"
gem "decidim-meetings"
gem "decidim-pages"
gem "decidim-budgets"
#gem "decidim-dev"
gem "decidim-surveys"
gem "decidim-assemblies"
gem "decidim-accountability"
gem "decidim-verifications"
gem "decidim-debates"
gem "decidim-sortitions"
gem "decidim-generators"
gem "decidim-blogs"
#gem "decidim-results"
gem "decidim-initiatives"
gem "decidim-consultations"
gem "decidim-forms"
gem "decidim-conferences"
#gem "decidim-plans"
gem "decidim-participatory_processes"
gem "decidim-elections"
gem "decidim-templates"
gem "decidim-calendar"
#gem "decidim-process_groups_content_block" >> Disable due to the error when updating
gem "decidim-navigation_maps", git: "https://github.com/Platoniq/decidim-module-navigation_maps"
#gem 'decidim-navbar_links', git: "https://github.com/OpenSourcePolitics/decidim-module-navbar_links"



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

