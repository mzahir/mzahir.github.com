---
layout: post
title: "Static Blogs"
date: 2013-03-29 21:13
comments: true
categories: technology tools
---

### Static What?

Static blogs are blogs that are composed of just a bunch of HTML files. There's no magic to it - No databases, WYSIWYG editors, etc. Just a bunch of files sitting on a webserver, waiting for a click or two.

### That sounds pretty lame

You're absolutely correct. Without any engine for the blog, there is no need for dynamic queries to the database. Whoa. There is no longer a need for a database.

### Y U No Like Databases?

![Select](https://dl.dropboxusercontent.com/sh/2blavl2u4awrtxz/-4fCFD5mZ4/static_yuno.jpg)

Well, you see - Databases are in the Spiderman camp. They come with great power but require an even greater responsibility. It's amazingly simple to screw your infrastructure up without proper upkeep of the database. If you're not keeping up with the security patches, a nasty exploit could be left open for all the horrible people out there to abuse your system.

### But my web servers don't get patched either
Compared to databases, web servers are simple, uncomplicated and lovable creatures. Sure, there are exploits even for web servers but they are far fewer than the ones out there for databases. If all you do is serve static pages that cannot and should not be modified by anyone, ever - It becomes a rather simple rule to enforce.

### Is there any non-database related reason to get a static blog?
Alright, Captain DBA. There actually is: When you take the complexity of a database out, in addition to making the response times significantly faster (by avoiding a call to a data tier), your data becomes static. The beauty of static is that you cache as much as you like without worrying about the validity of the data. Long story short, it makes your site faster. Snappier. Moar Better!

### Amazing! Can I pick one up at Walmart?
Unfortunately, not at Walmart. However, there are quite a few options available online. They differ in the language of implementation, how easy/flexible it is to theme, what comes out of the box and community plugins. 

The ones that have made this highly vetted list are:

* [Octopress](http://octopress.org/) / [Jekyll](http://jekyllrb.com/)
* [All these handsome search results on Github](https://github.com/search?q=static+blog)

Don't rush through that long list of two items. Let it soak in. Embrace the knowledge. 

### Cool tools to write?
One of my favorites is the ability to write in [Markdown](http://daringfireball.net/projects/markdown/). On Mac OS X I use [Mou](http://mouapp.com/) to write the articles. Since everything can also be managed within your version repository of choice, I throw a copy of my blog on [GitHub](https://github.com/mzahir/octopress). GitHub has formatting for Markdown so it's actually pretty easy to read posts right on Github. [Check it out](https://github.com/mzahir/octopress/tree/master/source/_posts). 

Some engines also provide syntax highlighting of code snippets through [Pygments](http://pygments.org/). Get your hack on!


### Does this mean that I'm reading this on a static blog?
Why, yes. Yes, you are.

![Select](https://dl.dropboxusercontent.com/sh/2blavl2u4awrtxz/Mrs6-_zPBh/static_select.jpg)



