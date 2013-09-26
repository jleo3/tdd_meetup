##You Only Have to Learn to Test Drive if You Want to Be a *Good* Developer

---
<aside class="notes">
<ul>
<li>
3 steps to getting started with rspec in your rails app.
<li>
I name all of my machines after musicians or bands.
<li>
TODO: configure minitest
</ul>
</aside>

##How to Get Up and Running
* Skip the test/ dirs with `rails new $app_name -skip-test-unit`
* Add `gem 'rspec-rails'` to Gemfile
* `rake generate rspec:install`

    joe@warpaint:~/dev/ga/temp/slacker$ rails generate rspec:install
          create  .rspec
          create  spec
          create  spec/spec_helper.rb

---
