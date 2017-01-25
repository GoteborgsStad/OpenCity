---
layout: page
title:  Installing
date:   2016-12-15 23:52:02
category: doc
order: 1
---


Execute the following steps In order to create a new GitHub-pages project using this template:

# Initialize the GitHub-pages project

1. [Create a new repository at GitHub](https://github.com/new). The URL to the page will become http://owner.github.io/project-name.
2. Clone the repository to your local machine, e.g. using `git clone git@github.com:owner/project-name.git` in a terminal.
3. Create new branch `gh-pages` on your local machine, e.g. using `git checkout -b gh-pages` in a terminal in your project path.
4. Create new remote `template` on your local machine pointing at this template, e.g. using `git remote add git@github.com:GoteborgStad/jekyll-docs-template.git` in a terminal in your project path.
5. Fetch remote `template` on your local machine, e.g. using `git fetch template` in a terminal in your project path.
6. Merge fetched data on your local machine, e.g. using `git merge template/gh-pages` in a terminal in your project path.
7. Commit merged data on your local machine, e.g. using `git commit -m "Merged from template"` in a terminal in your project path.
8. Push committed data to GitHub, e.g. using `git push` in a terminal in your project path.

You will now have a GitHub-pages site available at http://owner.github.io/project-name

# _config.yml

Edit _config.yml

1. `title` - Project name, visible in the top left corner of the GitHub-pages site.
2. `subtitle` - A tagline, visible to the right of the title.
3. `google_analytics_id` - Identity of Google analytics project if you want statistics from usage of your GitHub-pages site. Supplied by Google and looks Something like `UA-83704239-1`.
4. `sections` - Categories of your articles. Visible in the navigationbar to the left of your GitHub-pages site.

If you edited the file localy on your machine rather than online at GitHub you now need to commit and push the changes to GitHub:

1. Add the update file on your local machine, e.g. using `git add _config.yml` in a terminal in your project path.
2. Commit the added file on your local machine, e.g. using `git commit -m "Changed configuration for new site"` in a terminal in your project path.
3. Push the committed file to GitHub, e.g. using `git push` in a terminal in your project path.                                                                                   

# Remove template posts

Remove all `.md`-files in the directory `_posts`, either online at GitHub or on your local machine repository, e.g. using `git rm _posts/*.md` in a terminal in your project path. Commit and push, e.g. using `git commit -m "Removed old template posts` and `git push` in a terminal in your project path.
