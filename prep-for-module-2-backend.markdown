# Module 2 Prep Work

## Required Assignments

* 1.) HTML/CSS:
  * Self learning of CSS and HTML
  * Personal Site

* 2.) SQL & Sinatra assignments:
  * Web Guesser
  * Jumpstart Lab SQL Tutorial
  * Task Manager (Must be complete for the first day of class)


## HTML/CSS

### Task #1: Learn HTML and CSS Basics

Unless you have **significant** experience with HTML and CSS, choose one of these to complete:

1) [Shay Howe's Learn to Code HTML & CSS](http://learn.shayhowe.com/html-css/). Written tutorial. Super informative and comprehensive. Not obnoxious. Lots of hours.

2) [Khanacademy's HTML/CSS: Making Webpages](https://www.khanacademy.org/computing/computer-programming/html-css). Video and in-browser editor. Super informative, slightly obnoxious at points :) Approximately 3-6 hours.

3) [Code Academy's HTML/CSS Course](https://www.codecademy.com/learn/web). Interactive written tutorial. Fairly comprehensive. Approximately 5-7 hours.

### Task #2: Build a Personal Blog

Use the HTML and CSS skills you learned to build yourself a personal blog site. Choose your level of challenge: Mild, Medium, or Spicy.

1) Mild: Build a personal site with a blog portion using plain HTML and CSS. At minimum, your site should contain an `index.html`, `styles.css`, and a first blog post: `insert-first-post-title-here.html`. Push your project to Github Pages using the same instructions as for one using Jekyll [these instructions](https://github.com/turingschool/lesson_plans/blob/master/electives/jekyll-blog-github-pages/pushing-project-to-gh-pages.markdown).

2) Medium: Clone [this Jekyll starter repo](https://github.com/rwarbelow/yourusername.github.io). Remove the `.git` folder (`rm -rf .git`) and rename the repository so that your own github username replaces `yourusername` but keep `.github.io` on the end. Check out the README for instructions on how to view and modify your site. Push your project to Github Pages using [these instructions](https://github.com/turingschool/lesson_plans/blob/master/electives/jekyll-blog-github-pages/pushing-project-to-gh-pages.markdown). Reference the [Jekyll Docs](http://jekyllrb.com/docs/home/) for extra help.

3) Spicy: Use the [Jekyll Docs](http://jekyllrb.com/docs/home/) to set up your own blog. Push your project to Github Pages using [these instructions](https://github.com/turingschool/lesson_plans/blob/master/electives/jekyll-blog-github-pages/pushing-project-to-gh-pages.markdown).

### Task #3: Submit Your Personal Blog

Add a link to your personal webpage repository [here](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/2module/intermission_work/personal_site_html_css.yml) by **Thursday, September 29th**.

## SQL & Sinatra

### Task #1: [Web Guesser](http://tutorials.jumpstartlab.com/projects/web_guesser.html)

Build out base functionality and add at least one of the extensions. Approximately 1-3 hours. Add a link to your repository [here](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/2module/intermission_work/web_guesser.yml) by **Tuesday, September 27th**.

### Task #2: [Jumpstart Lab SQL Tutorial](http://tutorials.jumpstartlab.com/topics/sql/fundamental_sql.html)

Complete the Jumstart Lab SQL Tutorial. **Do not complete the Sequel tutorial linked at the bottom of the Jumpstart Lab page.**

### Task #3: [Task Manager](https://github.com/s-espinosa/task_manager_redux)

The entire tutorial will take approximately 1-3 hours. Build it once using the tutorial (*TYPE the code snippets -- do not copy!*), then try building it again with less reference to the tutorial. Add a link to your task manager repository [here](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/2module/intermission_work/task_manager.yml) by **Saturday, October 1st. __You will need to have this project finished before you can attend any class in module 2__.**

## Get Module 2 Tools

### Task #1: Install Rails

If you don't already have it: `gem install rails`.

### Task #2: Download Postgres

Download the [Postgres app](http://postgresapp.com/).

__OR: Use Homebrew to install Postgres:__

From your terminal, run:

```
brew update
brew install postgres
ln -sfv /usr/local/opt/postgresql/*.plist ~/Library/LaunchAgents
launchctl load ~/Library/LaunchAgents/homebrew.mxcl.postgresql.plist
```
[want to know a little more?](http://www.fyquah.me/setup-postgresql-on-os-x)

These last 2 lines will set up a special Daemon init file so that your operating
system will start postgres automatically whenever you log in.

## Optional Additional Prep Work

* [Design for Developers](http://webdesign.tutsplus.com/series/design-school-for-developers--webdesign-13793)
* [Codecademy's HTML/CSS Track](http://www.codecademy.com/en/tracks/web)
* [CodeSchool's Front-end Foundations Slides](http://courseware.codeschool.com/front-end-foundations/Front-end-Foundations.pdf)
* [HTML and CSS: Design and Build Websites](http://www.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189) (Great book and resource)
* [30 Days to Learn HTML & CSS](http://webdesign.tutsplus.com/courses/30-days-to-learn-html-css)
* [Sinatra: Up and Running](http://www.amazon.com/Sinatra-Up-Running-Alan-Harris/dp/1449304230/ref=sr_1_2?ie=UTF8&qid=1422133158&sr=8-2&keywords=sinatra+application)
* [Jump Start Sinatra](http://www.amazon.com/Jump-Start-Sinatra-Darren-Jones/dp/0987332147/ref=sr_1_1?ie=UTF8&qid=1422133181&sr=8-1&keywords=jumpstart+sinatra)
* [Introduction to Basics of HTTP](https://www3.ntu.edu.sg/home/ehchua/programming/webprogramming/HTTP_Basics.html)
* [Quick 15 minute video introduction to HTTP basics](https://www.youtube.com/watch?v=18XDokfwIDo)
* [What is HTML anyway? MDN's basics of HTML...  MDN==Mozilla Developer Network](https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/HTML_basics)

## Submissions:

* [Tuesday, September 27th - Web Guesser](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/2module/intermission_work/web_guesser.yml)
* [Thursday, September 29th - Personal Site](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/2module/intermission_work/personal_site_html_css.yml)
* [Saturday, October 1st - Task Manager](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/2module/intermission_work/task_manager.yml)
