---
comments: true
layout: post
title:  "What do I think of pre-compiling CSS?"
date:   2017-11-07 10:21:35 -0600
categories: jekyll update
---

### First of all: What is preproccessing CSS? ...

Preproccessing CSS is a new way maintaining, structuring, and configuring CSS code. 
There are a handful of useful preprocessors for CSS:  

{% highlight ruby %}
 SASS, or the newer SCSS
 LESS
 Stylus
{% endhighlight %}

And they all get rewritten into a regular CSS-code, however, they all have special features and slightly different but very much like the regular CSS syntax. 
For example, they make it possible to use functions, nest your code, use mixins and create variables for saving constants. 
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

So instead of searching all font-sizes and changing them thereafter the Variables makes it
possible to change all font-sizes in the same family at one place.

I think that preprocessing CSS is a bit strange at first, having codes that slightly differ from CSS
and in some way along the process of executing the code turns into CSS so that a browser can read it...
Strange.
But I could still see the benefits of having multiple files and divide your code if you are creating a bigger
website because of the easy maintenance property, using @import for example. 
This way its possible to separate code in smaller pieces for better maintainability and control
over the code.

My question is Why?
Why not just add/extend all these new features into the current CSS, so that you still are able to divide 
your project AND use functions, mixins, create variables within your code. I say this because of javascript. It is 
a big language, has a lot of users and still changes all the time (every year there is some new tweaks and addings to it). 
The old javascript code still works as users move over to easier solutions. 

I haven't really find an answer yet, and it was just a thought. In the mean time I will still use the preproccessors to see where they can take me..



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/



                            