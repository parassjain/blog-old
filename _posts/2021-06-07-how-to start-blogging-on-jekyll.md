---
layout: post
title:  "How to start blogging on jekyll"
date:   2021-06-07
categories: Daily-Learning
---

this post is about setting up Jekyll to start blogging(on linux)
i will be covering just jekyll part here, uploading on github pages will be in the next part 
-> [link]({{ site.baseurl }}{% post_url 2021-06-07-how-to-host-your-blog-on-github %})

prefer linux/macos over windows

go to website [jekyll docs](https://jekyllrb.com/docs/)
follow these 4 simple commands
1.  gem install jekyll bundler #this will installl the jekyll and the bundler gems.
2.  jekyll new myblog #this will create a blog template for you named myblog
3.  cd myblog #open and go insside the folder you just created
4.  bundle exec jekyll serve #build the site and make your server running
5.  Browse to [http://localhost:4000](http://localhost:4000)

Congratulation, your blog is up and running