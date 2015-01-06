# Kanzan Blog site

Available at http://blog.kanzan.io


## Prerequisites

This site is built using Jekyll. [Install Jekyll](http://jekyllrb.com/) before attempting to maintain the site or write new posts.

Deplyment automation is managed by [npm](https://www.npmjs.com) which is installed automatically as part of Node.


## Hosting and deployment

The site is hosted statically on Github Pages and deplyed by pushing the latest jekyll build to th gh-pages branch. 

An npm helper is setup to manage the git subtree and push this to the gh-branch.

1. Build the site with jekyll `jekyll build`
2. Add the output code to the git repo.
3. Push the output to gh-pages via npm `npm run deploy`

...done?
