---
layout: post
subtitle: new year, new test
---

| Description  | Reward  |
|---|---|
| Created a bug report for a podcasting app | $12 |
| Completed UX feedback of a security platform | $120 |
| Created a bug report for a website accepting an invalid email address | $3 |
| Created a bug report for a user being unable to decline marketing emails | $3 |
| Created a bug report for a members club not recognizing enrollment | $3 |
| Total | $141 |

My podcasting bug report had to do with resetting the cache. Essentially it would factory reset the settings, however I noticed that if you turned off notifications and performed the cache reset, any previously turned off notifications would be turned on, but if you were to subscribe to a new show, those notifications would default to being off. At the time, I didn't know where that would get me, but it felt like something was off. Thankfully, it turned out to be a "very valuable" bug.

The UX project was completely unexpected. $20 of it was making sure you had the right settings for ![OBS](https://obsproject.com/). The second part was reviewing a security platform and speaking your thoughts aloud as you watched videos and clicked through the site. I did something similar for a banking website, but I didn't need to shoot video and it wasn't worth nearly as much. If I'm lucky, more of those type of projects will come my way.

Having said that, I also received two bug rejections from the podcasting app. One was a toggle switch that magically appeared and disappeared with GDPR consent settings. I don't know if it was truly important, but because it was odd behavior I reported it. The other was related to changing the seek forward and backward times. Basically, if you updated your time from say, 15sec to 1min, the app would acknowledge you selected the change, but wouldn't update to the correct time. Although, I completed that at the same time as the caching error, my bug was labeled out of scope because of the build number.

> You win some, you lose some

Before this gets too long, I did want to say I was learning about invalid email accounts. Like, I knew there were some rules when it came to domains and symbols, but on a recent test I also learned that hyphens are only allowed under certain circumstances. The recent site that I tested would allow an email address like, a@b---------.com. Hyphens, as I learned, cannot be the first or last character, and cannot be added consecutively in a domain name. *The more you know*

I still haven't come across a big bug, but I'm taking it one day at a time.


$223.50 down, $776.50 to go. Time to file another bug report!