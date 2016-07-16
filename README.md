# My Awesome Rails Gem
My collection of awesome Ruby Gems for Rails development.

The goal is to help every Rails developer to build an awesome Rails product/service.

* [Rails Gem List](#rails-gem-list)
  * [User](#user)
  * [Active Record](#active-record)
  * [Plugins](#plugins)
  * [API](#api)
  * [Email](#email)
  * [File Uploading](#file-uploading)
  * [Searching](#searching)
  * [Scheduled/Recurrence Jobs](#scheduledrecurrence-jobs)
  * [View Helper](#view-helper)
  * [Environment Variables](#environment-variables)
  * [Admin Panel](#admin-panel)
  * [Logging](#logging)
  * [Debug](#debug)
  * [Coding Style](#coding-style)
  * [Testing](#testing)
  * [Production](#production)
  * [Error Logging](#error-logging)

## User

### Authentication
* [Devise](https://github.com/plataformatec/devise/) - Devise is a flexible authentication solution for Rails based on Warden.
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) - Token based authentication for Rails JSON APIs.

### Authorization
* [cancancan](https://github.com/CanCanCommunity/cancancan) - Continuation of CanCan, the authorization Gem for Ruby on Rails.CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access. All permissions are defined in a single location (the Ability class) and not duplicated across controllers, views, and database queries.
* [rolify](https://github.com/RolifyCommunity/rolify) - Role management library with resource scoping.


### Omniauth
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook)
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter)
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2)

## Active Record
* [FriendlyId](https://github.com/norman/friendly_id) - FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models.
* [PaperTrail](https://github.com/airblade/paper_trail) - PaperTrail lets you track changes to your models' data. It's good for auditing or versioning.
* Tagging
  * [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.
  * [closure_tree](https://github.com/mceachen/closure_tree) - Easily and efficiently make your ActiveRecord models support hierarchies.

## Plugins
* [Chartkick](https://github.com/ankane/chartkick) - Chartkick helps your to create beautiful Javascript charts with one line of Ruby.
* [CKEditor](https://github.com/galetahub/ckeditor) - CKEditor is a WYSIWYG text editor designed to simplify web content creation. It brings common word processing features directly to your web pages. Enhance your website experience with our community maintained editor. [ckeditor.com](http://ckeditor.com)

## API
* [Grape](https://github.com/ruby-grape/grape) - Microframework to create REST-ful APIs in Ruby.
* Documentation
	* [Grape Swagger](https://github.com/ruby-grape/grape-swagger) - Autogenerate documentation on Grape API.

## Email
* [letter_opener](https://github.com/ryanb/letter_opener) - Preview mail in the browser instead of sending.

## File Uploading
* [Paperclip](https://github.com/thoughtbot/paperclip) - Easy file attachment management for ActiveRecord.

## Searching
* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) - Elasticsearch integrations for ActiveModel/Record and Ruby on Rails.

## Scheduled/Recurrence Jobs
* [Sidekiq](https://github.com/mperham/sidekiq) - Simple, efficient background processing for Ruby.

## View Helper
* [meta-tags](https://github.com/kpumuk/meta-tags) - Search Engine Optimization (SEO) plugin for Ruby on Rails applications.

## Admin Panel
* [ActiveAdmin](http://activeadmin.info) - ActiveAdmin is a administration framework for Ruby on Rails applications.

## Logging
* [Ahoy](https://github.com/ankane/ahoy) - Ahoy provides a solid foundation to track visits and events in Ruby, JavaScript, and native apps.

## Debug
* [byebug](https://github.com/deivid-rodriguez/byebug) - Byebug is a simple to use, feature rich debugger for Ruby 2. It uses the new TracePoint API for execution control and the new Debug Inspector API for call stack navigation, so it doesn't depend on internal core sources.

## Coding Style
* [RuboCop](https://github.com/bbatsov/rubocop) - Rubocop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide).

## Testing
* [rspec-rails](https://github.com/rspec/rspec-rails) - Rspec-rails is a testing framework for Rails 3.x and 4.x.
* [Capybara](https://github.com/jnicklas/capybara) - Capybara helps you test web applications by simulating how a real user would interact with your app. And drivers:
* [factory_girl](https://github.com/thoughtbot/factory_girl) - Factory_girl is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance.
* [factory_girl_rails](https://github.com/thoughtbot/factory_girl_rails) - Factory_girl_rails provides Rails integration for factory_girl.
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Database Cleaner is a set of strategies for cleaning your database in Ruby.Support ActiveRecord, DataMapper, Sequel, MongoMapper, Mongoid, CouchPotato, Ohm and Redis.
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Shoulda-matchers provides serveral matchers for testing common Rails functionality.
* [ResponseCodeMatchers](https://github.com/r7kamura/response_code_matchers) - ResponseCodeMatchers provides rspec matchers to match http response code.

### Security
* [brakeman](https://github.com/presidentbeef/brakeman) - Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities.
* [bundle-audit](https://github.com/rubysec/bundler-audit) - bundler-audit is a patch-level verification tool for Bundler which checks for vulnerable versions of gems and insecure gem sources.
* [Secure Headers](https://github.com/twitter/secureheaders) -  Secure Headers will automatically apply several headers that are related to security.

## Production
* [Capistrano](https://github.com/capistrano/capistrano) - Remote multi-server automation tool.

## Error Logging
* [Rollbar](https://github.com/rollbar/rollbar-gem) - Exception tracking and logging from Ruby to Rollbar.
