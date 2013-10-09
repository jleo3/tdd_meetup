##Agenda
* Rant, Rave, make Dramatic Hand Gestures
* Calmly test drive something
* Where to Learn More

---

<aside class="notes">
When I have to be, I'm this kind of zealot.
</aside>

<img src="../../assets/enforcer.jpg" height="400" width="550">
##Disclaimer: I am a testing zealot

---

<img src="../../assets/testing.jpg" height="400" width="550">
##Disclaimer: I am a testing zealot

---

<aside class="notes">
<ul>
<li>
TDD and BDD are too similar to swear allegiance to one or the other. Pick one that you like and move on with your life. 
<li>
If you sit down with someone who loves a particular framework, use it!
</ul>
</aside>
  
##Testing Guidelines

![haterade](../../assets/haterade.gif)

* TDD and BDD: don't discriminate

---
<aside class="notes">
<ul>
<li>
This one is where I am rightly called a zealot. There are many people who test last. Some of them may even do it successfully.
<li>
The only way to ensure safety _and_ quality of design (think Sandi Metz and Bob Martin) is to test first.
</ul>
<li>
You are building code for reuse and the first use of your code is your tests.
</aside>

##Testing Guidelines

* Test First > Test Last
* WWSMD?

![wwsmd](../../assets/wwsmd.jpg)

---
<aside class="notes">
<ul>
<li>
This one I'm serious about. Our industry is starving for developers. We need them so badly that we'll take average talent, average effort and we'll even pay a lot for it. What we're left with is average products that fail in spectacular and unanticiapated ways.
<li>
You can join the ranks of the mediocre easily. It's a low bar to cross. But if you want to be great, you have to test drive. I am an easy-going guy but I don't compromise on this. There's too much at stake.
<li>
I can tell you test driven code from non test-driven code in 2 seconds and I don't even need to see the tests. At a certain point it becomes obvious, second nature. You can feel the presence of testing and competency.
<li>
Our Users deserve better than they have right now. They deserve quality, craftsmanship, attention to detail. This is how you give it to them.
</ul>
</aside>

##Testing Guidelines

* You Should Only Learn to Test Drive if You Want to Be a *Good* Developer

---

## `</rant>`

---

##What Does Good Testing Look Like?
![loc](../../assets/loc.png)


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

##Alternative
* [rails composer](http://railsapps.github.io/rails-composer/)
* `rails new myapp -m https://raw.github.com/RailsApps/rails-composer/master/composer.rb`
* Select server, database, template engine, test framework, and more

---

##Test Driving
###Start with the Expectations

---

##Test Driving
###Test Outside-In

---
##What did we learn?

* Test first isn't easy and it's not always fast
* Let the code guide you: I test drove through three classes without looking at the browser.
* There's _so_ much to learn

---
##Great Frameworks in Testing

* RSpec
* MiniTest
* Jasmine
* Capybara

---
##Great Minds in Testing

* Brian Marick
* Nat Pryce
* Steve Freeman
* Roy Osherove
* Dave Thomas
* Kent Beck
* Bob Martin
* David Chelimsky

---
##Great Texts in Testing

* [Growing Object Oriented Software, Guided by Tests](http://www.amazon.com/Growing-Object-Oriented-Software-Guided-Tests/dp/0321503627) (the "GOOS" book)

  * Nat Pryce and Steve Freeman
* [xUnit Test Patterns: Refactoring Test Code](http://www.amazon.com/xUnit-Test-Patterns-Refactoring-Code/dp/0131495054/ref=sr_1_1?s=books&ie=UTF8&qid=1381193288&sr=1-1&keywords=xunit+test+patterns+refactoring+test+code)
  * Roy Osherove

