---
comments: true
layout: post
title:  "What do I think of pre-compiling your CSS?"
date:   2017-11-07 10:21:35 -0600
categories: jekyll update
---

### First of all: What is preproccessing CSS? ...

Preproccessing CSS is a new way maintaining, structuring, and konfiguring CSS code.
There are a handfull of usefull preprocessors for CSS:  

{% highlight ruby %}
 SASS, or the newer SCSS
 LESS
 Stylus
{% endhighlight %}

And they all support CSS, how ever, they all have special features and their own syntax.
For example, they all make it possible to create Variables for saving constans. This is how it can
look in :

{% highlight ruby %}
CSS:

div {
    font-size: 16px;
}


LESS: 

@font-size: 16px;

div {
    font-size: @font-size;
}
{% endhighlight %}

So instead of seraching all font-sizes and changing them thereafter the Variables makes it
possible to change all font-sizes in the same family at one place.




[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/



                            