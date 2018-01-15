---
comments: true
layout: post
title:  "Open Graph"
date:   2017-11-07 10:21:35 -0600
categories: jekyll update
---

Open graph is a feature you can use for choosing your presentation on facebook, or other social medias
where people link/share your website. Open graph makes your website into an object where you can choose your site title (insted of a url), you are able to write a small description of your website and choose a picture that suits for your purpose. This becomes a small presentation which takes place in addition to a post in an textfield.


#### This is how mine looks: 

{% highlight ruby %}

<meta property="og:title" content="My Awesome Page"/>
<meta property="og:type" content="website"/>
<meta property="og:url" content="http://localhost:4000/about/"/>
<meta property="og:image" content="https://ibb.co/kYDy7b"/>
<meta property="og:description" content="Me just coming from the store.."/>
<meta property="og:site_name" content="http://localhost:4000/"/>
<meta property="og:fb:admins" content="1102711847"/>


{% endhighlight %}



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
