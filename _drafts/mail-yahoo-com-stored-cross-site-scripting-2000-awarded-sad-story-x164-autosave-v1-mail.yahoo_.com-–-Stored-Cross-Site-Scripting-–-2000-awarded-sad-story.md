---
id: 167
title: 'mail.yahoo.com – Stored Cross-Site Scripting – $2,000 awarded [sad story]'
date: 2019-01-17T17:37:43+00:00
author: admin
layout: revision
guid: https://syzhack.com/blog/index.php/2019/01/07/164-autosave-v1/
permalink: /index.php/2019/01/17/164-autosave-v1/
---
<img class="wp-image-161 aligncenter" src="https://syzhack.com/blog/wp-content/uploads/2019/01/yahoo-76684_1280-766x395.png" alt="" width="303" height="156" />

Hello guys, today I will share my sad Bug Bounty hunting story.

Everything started when I read some Bug  Bounty articles of the Yahoo giant who inspired me to found this bug, among those articles, were those of security researcher Jouko Pynnönen.

He found two Stored Cross-Site Scripting bugs in mail.yahoo.com sub-domain and he got for every bug $10,000, that happened in 2015 &#8211; 2016.

<img class="alignnone size-full wp-image-160" src="https://syzhack.com/blog/wp-content/uploads/2019/01/download.png" alt="" width="1355" height="228" /> 

Full articles:

• https://klikki.fi/adv/yahoo.html

• https://klikki.fi/adv/yahoo2.html

&nbsp;

2017 &#8211; Mrityunjoy found the same vulnerability type in the same sub-domain, yes&#8230; he got $10,000 for that.

&nbsp;

Full article:

• https://www.facebook.com/notes/mrityunjoy-emu/yahoo-mail-box-stored-xss-write-upbounty-rewarded-10000-usd/677948372401448/

* * *

&nbsp;

I found same vulnerability type in the same sub-domain and I got $2,000, it&#8217;s that correct?! 🤔 I want to say that: I reported the bug when the Yahoo Bug Bounty action alone. At the moment  Yahoo made a partnership with Oath.

Ok, let&#8217;s see my proof of concept video, but first special thanks to Dan Cezar (another skilled guy ).

### #Description:

I bypassed the filter via HTML malformed tags in e-mail signature. The important thing: the XSS was active when the victim reply to the e-mail.

**Payload:** _&#8220;</a><img ismap=&#8217;xxx&#8217; itemtype=&#8217;yyy&#x27; style=width:100%;height:100%;position:fixed;left:0px;top:0px; onmouseover=alert(/XSS/)//&#8217;>_

### #Vulnerability type:

Stored Cross-Site Scripting

### #Author:

Măgherușan Ovidiu Teodor  
—-

### #Proof of concept:



&nbsp;

### #Timeline: {#a384.graf.graf--h3.graf-after--p}

Jul 10th, 2018 &#8211; Bug subbmited.

Jul 11th, 2018 &#8211; Reply by me with more information, that worked on last version of Google Chrome.

Jul 11th, 2018 &#8211; Triaged.

Jul 12th &#8211; Aug 15th, 2018 &#8211; More replies about severity score.

Aug 30th, 2018 &#8211; Someone talking to me after 27 days without response.

Sep 24th &#8211; Nov 8th , 2018 &#8211; Another replies with more details, severity score links, proof of concept videos and external links.

Nov 8th, 2018 &#8211; Finally, after 4 months I receive bounty ammount $2,000.

Nov 30th, 2018 &#8211; Bug it&#8217;s repaired.

&#8212;

### #Feedback: {#a384.graf.graf--h3.graf-after--p}

The progress and expectations of Yahoo&#8217;s Bug Bounty Program have not been great.

When can I give a note from 1 to 10, that can be 5.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;