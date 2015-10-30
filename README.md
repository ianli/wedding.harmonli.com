Beth and Ian's Wedding Site
===========================

Development Setup
-----------------

Create workspace

  > jekyll new wedding.harmonli.com
  > cd wedding.harmonli.com
  > npm init

Create GitHub repository and associate with workspace

  > git init
  > git add .
  > git commit -m "First commit"
  > git remote add origin https://github.com/ianli/wedding.harmonli.com.git
  > git push -u origin master

Create gh-pages branch.
[Refer to this](http://brettterpstra.com/2012/09/26/github-tip-easily-sync-your-master-to-github-pages/), but keep the master branch
so we can commit versions without changing what is published.

  > git branch gh-pages
  > git rebase master gh-pages
  > git push origin gh-pages
