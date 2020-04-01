---
id: 220
title: 'mail.yahoo.com &#8211; Stored Cross-Site Scripting &#8211; How I missed the reward of $10,000'
date: 2019-06-11T18:43:28+00:00
author: admin
layout: post
guid: https://syzhack.com/blog/?p=220
permalink: /index.php/2019/06/11/mail-yahoo-com-stored-cross-site-scripting-how-i-missed-the-reward-of-10000/
nullpoint_basic_post_layer_select:
  - 1-col
nullpoint_post_allow_breadcrumbs:
  - 'no'
nullpoint_post_nav:
  - 'no'
categories:
  - bug bounty
---
<img class="wp-image-161 aligncenter" src="https://syzhack.com/blog/wp-content/uploads/2019/01/yahoo-76684_1280-766x395.png" alt="" width="332" height="171" />

#### **&#8220;Sometimes, alert() just isn&#8217;t scary enough.&#8221; &#8211; **that happened in my case.

&nbsp;

At Jul 11th, 2018 I reported a Stored Cross-Site Scripting in <span class="js-display-url">mail.yahoo.com</span><span class="tco-ellipsis"><span class="invisible"> </span></span> and I got $2,000. If I compare the reward amounts between me and another researcher&#8230; will be a big difference. For example, if we follow this **[report](https://twitter.com/klikkioy/status/1096424444598382595)** we can see that the researcher has found the same vulnerability type in the same domain and he got $10,000.

Another reports:

<div id="fb-root">
</div>



<div class="fb-post" data-href="https://www.facebook.com/notes/mrityunjoy-emu/yahoo-mail-box-stored-xss-write-upbounty-rewarded-10000-usd/677948372401448/" data-width="750">
  <blockquote cite="https://www.facebook.com/notes/mrityunjoy-emu/yahoo-mail-box-stored-xss-write-upbounty-rewarded-10000-usd/677948372401448/" class="fb-xfbml-parse-ignore">
    <p>
      Posted by <a href="https://www.facebook.com/mitun.joy.75">Mrityunjoy Emu</a> on&nbsp;<a href="https://www.facebook.com/notes/mrityunjoy-emu/yahoo-mail-box-stored-xss-write-upbounty-rewarded-10000-usd/677948372401448/">Tuesday, 11 July 2017</a>
    </p>
  </blockquote>
</div>

or

https://klikki.fi/adv/yahoo.html

or

https://klikki.fi/adv/yahoo2.html

I tried to obtain information about the differences between reward reports but without results. I asked for public disclosure and&#8230; without any clear answer.

&nbsp;

I don&#8217;t have permission for public disclosure, but I give you a screen of the report.

<img class="alignnone size-full wp-image-221" src="https://syzhack.com/blog/wp-content/uploads/2019/06/Screenshot_5.png" alt="" width="1167" height="476" /> 

I want to specify that in this case participated a number of 6 Security Analysts for a period of 9 months. In that time Yahoo made a partnership with OATH and then with Verizon Media, at the same time a part of the rules have been changed.

&nbsp;

I will update the timeline, maybe I will have permission for public disclosure.

&nbsp;

Bye! ✌

&nbsp;

&nbsp;

&nbsp;

&nbsp;