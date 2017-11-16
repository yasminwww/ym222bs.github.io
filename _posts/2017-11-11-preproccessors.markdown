---
comments: true
layout: post
title:  "What do I think of pre-compiling your CSS?"
date:   2017-11-07 10:21:35 -0600
categories: jekyll update
---

### First of all: What is preproccessing CSS? ...

Preproccessing CSS is a new way maintaining, structuring, and configuring CSS code. 
There are a handfull of usefull preprocessors for CSS:  

{% highlight ruby %}
 SASS, or the newer SCSS
 LESS
 Stylus
{% endhighlight %}

And they all get rewritten into a regular CSS-code, however, they all have special features and their own syntax.
For example, they make it possible to use functions, nest your code, use mixins and create variables for saving constans. 
This is how it can look in :

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

I think that preprocessing CSS is a bit complicated at first but I can still see
the benefits of having multiple files and devide your code if you are creating a bigger
website because of the easy maintenance property, using @import for example. 
This way its possible to separate code in smaller pieces for better maintainability and control
over the code. And that seems fine to me. But...

My question is Why?
Why not just add/extend all these new features into the current CSS, so that you still are able to divide 
your project AND use funtions, mixins, create variabels within your code. I cant really find an answer
to my question when i googled it.

Jekyll on the other hand...
if I would have a strong idea
of how things should look from the beginning then I probably would create the website from scratch, 
instead of using Jekyll for example.

Otherwise, Jekyll has alot of themes and layouts and features that are reday
to use and is written in scss/html/css.


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/



                            