---
layout: post
title: "Week 13: Takeaways App Week 1"
date: 2014-05-19 18:00:00
---

Tonight we start on our first real client app. We will be using Ruby 2.1.2 and Rails 4.1.1

Upgrading ruby (using rvm)

  1. `rvm get head` - upgrades rvm
  2. `rvm install 2.1.2` - installs the latest version of ruby
  3. `ruby -v` to check that we're using ruby 2.1.2p95

Install latest rails

  1. `gem install rails`
  2. `rails -v` to ensure we're using rails 4.1.1

Downloading setting up the project

  1. cd into your workspace directory
  2. Clone the [durango-ruby-school/takeaways][1] repo. Use the SSH clone url.
  3. cd into the takeaways folder and follow the setup instructions in README.md

Project management

  1. [Fast Signs app Trello Board][3]

## Helpful git commands

* `git checkout -b <branch name>` Create and check out a new brnach
* `git status` shows you the files you've changed and which branch you're on
* `git push origin <branch name>` Push your new branch up to github
* `git pull origin master` - Pulls the latest changes from master. Can also replace master with a branch name you want to pull.

Cool git branching tutorial: http://pcottle.github.io/learnGitBranching/. Also review code school's [Try Git][4].


## Recommended reading

1. [The HTML and CSS Book][2]


[1]: https://github.com/durango-ruby-school/takeaways
[2]: http://www.amazon.com/gp/product/1118008189/ref=as_li_tf_tl?ie=UTF8&tag=httpwwwhtmlan-20
[3]: https://trello.com/b/d2xdfz5D/fastsigns-app
[4]: https://try.github.io
