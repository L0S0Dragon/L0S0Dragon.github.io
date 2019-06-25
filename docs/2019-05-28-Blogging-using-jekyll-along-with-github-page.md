---
layout: post
title:  "Blogging using Jekyll along with Github page"
date:   2019-05-28 11:18:21 +0800
categories: jekyll update
nav_order: 2
---
# Navigation Structure
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Set up the environment 

+ Install homebrew 
+ Install rbenv and ruby-build (brew install rbenv ruby-build)
+ Install a Ruby version (rbenv install 2.6.0)
+ Set the global ruby version (rbenv global 2.6.0)
+ Restart your Mac

See more for [set of environment][set-of-environment]  

[set-of-environment]:https://www.codementor.io/akabiru/3-steps-set-up-ruby-environment-macos-6mavm7jrl

## Install Jekyll 

+ gem install jekyll bundler
+ jekyll new myblog
+ cd myblog
+ bundle exec jekyll serve
+ Open the url displayed in the terminal

See more for [installation of jekyll][installation-of-jekyll] 

[installation-of-jekyll]:https://jekyllrb.com/docs/

## Deploy blogs to remote repository of github page
+ Register an account in [github pages][github-register] 
+ Create a new repository named as 'username.github.io'
+ Install [Git on your operation system][Installation-of-Git]

[github-register]:https://github.com
[Installation-of-Git]:https://www.atlassian.com/git/tutorials/install-git

+ Change directory to your blog	
+ Perform commands listed below
```
git init
git add --all
git commit -m
git remote add origin https://github.com/
usernameusername.github.io.git
git push -u origin master
```
+ If you get an error: permission denied (publickey), here is a page to help you find the [solution][Permission-denied] 

[Permission-denied]:https://help.github.com/en/articles/error-permission-denied-publickey

## Configure your page
+ Choose theme from [jekyll themes][jekyll-theme]
+ Install the theme you chosen 
+ Configure colors, fonts and other things by your favor
+ To find more about jekyll, it is useful to check the [usage documentation]

[jekyll-theme]:https://jekyllthemes.io/theme/
[usage documentation]:https://jekyllrb.com/docs/

##Install mathjax
[Link button](http://example.com/){: .btn }