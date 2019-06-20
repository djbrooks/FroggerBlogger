# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration
Modify app/models/post.rb file PER_PAGE = N value to how many Blog posts
are on each page. Use PER_PAGE = 3 if you want to see the apple_pagination
footer paginate after 3 blogs posts, else 6 looks good (two rows of three).


* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)
rails s

* Deployment instructions
Update herokupapp "Production" server (https://frogger-blogger.herokuapp.com/)
Commit all chgs to master on github. - Run cmd:
    "git push production master"
Should automagically deploy from github to Herokuapp.com.
