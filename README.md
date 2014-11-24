== Rails Template

* Ruby version
2.1.1

* Rspec

rails generate rspec:install

config/application.rb
 config.generators.test_framework  = :rspec

* Slim

config/application.rb
  config.generators.template_engine = :slim

* Sass

config/application.rb
  config.sass.preferred_syntax      = :sass
  config.sass.line_comments         = false
  config.sass.cache                 = false

* Factory Girl

spec/rails_helper.rb
  config.include FactoryGirl::Syntax::Methods
