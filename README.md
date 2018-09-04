# facebook.net
rails new social_register
gem 'devise'
gem 'omniauth'
gem 'omniauth-facebook'
bundle
rails g controller home
root to: "home#index"
