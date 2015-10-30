Beth and Ian's Wedding Site
===========================

Setup
-----

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
Keep the master branch so we can commit versions without changing
what is published.

  > git branch gh-pages
  > git rebase master gh-pages
  > git push origin gh-pages
