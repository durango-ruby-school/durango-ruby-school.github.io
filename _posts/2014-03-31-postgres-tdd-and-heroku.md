---
layout: post
title: "Week 7: Postgres, TDD and Heroku"
date: 2014-03-31 18:00:00
---

This week covers Postgres, the basics of TDD and deploying to heroku. Check out the [instructor notes][1].

Resources

  * [Capybara][2]
  * [RSpec Core Docs][3]
  * [Strong Parameters][4]
  * [Strong parameters Railscast][5]


Homework

* Thoughtbot Test-Driven Rails - Intro Video and Writing Integration Tests Video
    * This app is built with rails 3.2. When creating their app, run

        ```
        $ rails _3.2.17_ new todos --skip-test-unit
        ```
    * The videos use an older version of Capybara (1.1.4), than what we used in class (2.2.1). Here are the differences that you'll run into
        * Where integration specs are stored
          * 2.2.1 - spec/features
          * 1.1.4 - spec/integration
        * Matching page title
          * 2.2.1 - `expect(page).to have_title("My title")`
          * 1.1.4 - `expect(page).to have_css "title", text: "My title"
* Try following the tdd process for creating students



[1]: https://github.com/durango-ruby-school/Instructor-Notes/blob/master/Week-07-Postgres-Heroku-and-Intro-To-TDD.md
[2]: https://github.com/jnicklas/capybara
[3]: https://www.relishapp.com/rspec/rspec-core/v/2-14/docs
[4]: https://github.com/rails/strong_parameters
[5]: http://railscasts.com/episodes/371-strong-parameters
