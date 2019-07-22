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

About page looks funny (very thin card). MUST use bootstrap 4.0.0.alpha3.
Not sure the issue, but that version solves the About page format issue.

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Test on local machine
rails s # Start Rails server
Start Postgres db (gui?)
http://localhost:3000 URL to view env

* Deployment instructions
git add
git commit
git push
# Update herokupapp "Production" server (https://frogger-blogger.herokuapp.com/)
Commit all chgs to master on github (see above). Then run these Heroku cmds:
    "heroku login"
    "git push production master"
Should automagically deploy from github to Herokuapp.com and restart
the server.
