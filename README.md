# README

### rails generate graphql:install to install graphql
### install it as a gem like so 
### insert `gem 'graphql'` into the Gemfile as well as replace gem ### :development do with this`group ### :development do
###  gem 'listen', '~> 3.3'
###  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
###  gem 'spring'
###  gem 'graphiql-rails'
###  gem 'faker'
### end`

### then go into application.rb in the config folder and uncomment #require "sprockets/railtie" and activate it.
### then go back into the root of the app and create an assets folder within app and then a conifig folder within assets and a manifest.js with //= link graphiql/rails/application.css
### //= link graphiql/rails/application.js
### Now if you want to check out the graphql GUI simply on the browser enter localhost:3000/graphiql
### Also check the routes folder to properly see the routing for this app.

