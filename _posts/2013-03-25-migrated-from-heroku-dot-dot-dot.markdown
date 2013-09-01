---
layout: post
title: "Migrated from Heroku..."
date: 2013-03-25 23:07
comments: true
categories: cloud
---

<div about='http://farm2.static.flickr.com/1165/644335254_4b8a712be5.jpg'><a href='http://www.flickr.com/photos/nirak/644335254/' target='_blank'><img xmlns:dct='http://purl.org/dc/terms/' href='http://purl.org/dc/dcmitype/StillImage' rel='dct:type' src='http://farm2.static.flickr.com/1165/644335254_4b8a712be5.jpg' alt='Clouds by karindalziel, on Flickr' title='Clouds by karindalziel, on Flickr' border='0'/></a><br/><a rel='license' href='http://creativecommons.org/licenses/by/2.0/' target='_blank'><img src='http://i.creativecommons.org/l/by/2.0/80x15.png' alt='Creative Commons Attribution 2.0 Generic License' title='Creative Commons Attribution 2.0 Generic License' border='0' align='left'></a>&nbsp;&nbsp;by&nbsp;<a href='http://www.flickr.com/people/nirak/' target='_blank'>&nbsp;</a><a xmlns:cc='http://creativecommons.org/ns#' rel='cc:attributionURL' property='cc:attributionName' href='http://www.flickr.com/people/nirak/' target='_blank'>karindalziel</a><a href='http://www.imagecodr.org/' target='_blank'>&nbsp;</a></div>
<br>
After letting my blog idle for an year, I figured it was time to get back to some writing. Unfortunately (or perhaps fortunately), [Octopress](http://octopress.org/) had a few too many updates for me to apply them painlessly.

I ended up going through a bit of a manual update process. However, Heroku was rather unimpressed with the updated Sinatra application. This wasn't the first time this week that I've run into issues deploying apps to Heroku. If only there was another easy to use, hacker friendly Ruby PaaS. Enter, [Cloud Foundry](http://www.cloudfoundry.com/). ([EngineYard](https://www.engineyard.com/)? Sure, they are worthy of a mention too but they were third on my list and I never got that far down the list). 

Even though the [vmc](http://docs.cloudfoundry.com/tools/vmc/vmc-quick-ref.html) command doesn't show as much information as [heroku's toolbelt](https://toolbelt.heroku.com/), the interactive wizard-like prompts make it easier for newcomers to adapt. The CF apps also don't get passivated as frequently as Heroku's (if ever?). 

Here's to (hopefully) more writing! :)
