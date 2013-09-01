---
layout: post
title: "Seeing with CTags"
date: 2013-04-08 20:53
comments: true
categories: rails ruby technology unix
---

Within all hackery, the road to mastery usually leads you  to the nitty gritty low-level implementation details of what you are trying to grasp. Even though there are many books on advanced material, they only get you so far before you find that they are either no longer up-to-date or they don't cover a particular edge case that is imperative for you.

## To the source?! Uhh….
Despite the optimistic battle cry, reading the source code of a complex application/framework/language can be daunting, if not rather dry and immensely boring. Most of it isn't intended to be read as a book and before you know it, you're looking for the good parts. Just a specific portion that you'd like to understand instead of all that bloat in place to support stuff you don't care about.

![Select](https://dl.dropboxusercontent.com/sh/2blavl2u4awrtxz/ywt90ML4OJ/honeybadger.png)

## CTags to the rescue!

CTags will go through and create an index (or tag) file that allows you to search dynamically. I'm assuming that you're using vim as your text editor - there are flavors for Emacs, etc. that may suite you better.

## Setup

#### Installation

The easiest way is through homebrew. 
{% highlight bash %}
brew install ctags
{% endhighlight %}

#### Configuration
Suppose you're interested in rails. Grab a copy of the source
{% highlight bash %}
git clone git://github.com/rails/rails.git
{% endhighlight %}

Now you want to have ctags index those files but since vim will look for the tags file in the current directory and keep searching one level above, let's run this command from the user home (or the root directory that contains all of your rails projects)

{% highlight bash %}
cd <projects-root>
ctags -R ./path/to/rails/source

{% endhighlight %}

Add the following lines to your .vimrc file:
{% highlight bash %}
filetype on
set tags=tags;/
{% endhighlight %}


### Use The Source, @your_name
Fire up a new shell and go over to any rails project. Over a rails method (for example, create_after), hit ctrl+] to see the definition in the source. You can toggle back to where you were before using ctrl+t. Pretty sweet, huh?

There are additional shortcuts to listing matches, etc. that you can see for ctags either through the man pages or online. 

Blaze away and learn the underlying framework with ease, one method call at a time.
