# Pageflow Before After

Page type showing before/after image sliders (Digit style).

## Installation

Add this line to your application's Gemfile:

    # Gemfile
    gem 'pagflow-before-after'

Register the page type:

    # config/initializers/pageflow.rb
    Pageflow.configure do |config|
      config.register_page_type(Pageflow::BeforeAfter::PageType.new)
    end
    
Include javascripts and stylesheets:

    # app/assets/javascripts/application.js
    //= require "pageflow/before_after"

    # app/assets/javascripts/editor.js
    //= require "pageflow/before_after/editor"

    # app/assets/stylesheets/application.scss.css
    @import "pageflow/before_after"
    
Restart the application server.
