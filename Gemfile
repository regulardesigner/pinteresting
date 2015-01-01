source 'https://rubygems.org'

# bootstrap gem
gem 'bootstrap-sass'
# rails install basic gem without comments lines
gem 'rails', '4.1.5'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development

# sqlite3 fonctionne bien avec Rails parcontre sur le serveur Heroku postgre fonctionne mieux.
# sqlite3 pour la version de dev et test sur ma machine
group :development, :test do
     gem 'sqlite3'
end
# pg = postgre pour la version de production sur heroku branch master
group :production do
     gem 'pg'
     gem 'rails_12factor'
end

