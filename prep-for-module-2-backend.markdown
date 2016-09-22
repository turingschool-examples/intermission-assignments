# Module 2 Prep Work

## Required Assignments

* 1.) HTML/CSS:
  * Self learning of CSS and HTML
  * Personal Site

* 2.) Sinatra assignments:
  * Web Guesser
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

Add a link to your personal webpage repository [here](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/module_2_prep/personal_site_html_css.yml) by **Thursday, September 29th**.

## Sinatra

### Task #1: [Web Guesser](http://tutorials.jumpstartlab.com/projects/web_guesser.html)

Build out base functionality and add at least one of the extensions. Approximately 1-3 hours. Add a link to your repository [here](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/module_2_prep/web_guesser.yml) by **Tuesday, September 27th**.

### Task #2: [Task Manager](https://github.com/JumpstartLab/curriculum/blob/master/source/projects/task_manager.markdown)

The entire tutorial will take approximately 1-3 hours. Build it once using the tutorial (*TYPE the code snippets -- do not copy!*), then try building it again with less reference to the tutorial. Add a link to your task manager repository [here](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/module_2_prep/task_manager.yml) by **Saturday, October 1st. __You will need to have this project finished before you can attend any class in module 2__.**


A lot of what we do as developers is storing, manipulating, and tracking data. In order to do that we have many differnt data stores available to us. Arrays, hashes, CSVs, databases etc. What we do in task manager is use YAML, a ruby data store, to track our data. We use YAML in place of a more tradition database, like Postgresql, at the beginning of this module so we can visualy see our data as we input it and manipulate it. Basically it's a good starting point. These are YAMLs self-proclaimed goals:

```
The design goals for YAML are, in decreasing priority:

YAML is easily readable by humans.
YAML data is portable between programming languages.
YAML matches the native data structures of agile languages.
YAML has a consistent model to support generic tools.
YAML supports one-pass processing.
YAML is expressive and extensible.
YAML is easy to implement and use.
```

I bring this up because YAML is often a source of frustration for mod2 students, and it's nothing to be frustrated about. It's just a place to store data. We interact with YAML data with hash like syntax. [Here is a good link to learn more about YAML.](http://davesrubyrails.blogspot.com/2013/03/yaml-basics-and-some-simple-examples.html)

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

* [Tuesday, September 27th - Web Guesser](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/module_2_prep/web_guesser.yml)
* [Thursday, September 29th - Personal Site](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/module_2_prep/personal_site_html_css.yml)
* [Saturday, October 1st - Task Manager](https://github.com/turingschool/ruby-submissions/blob/master/1608-b/module_2_prep/task_manager.yml)
