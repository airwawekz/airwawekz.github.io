---
id: 215
title: 'ggg[[constructor.constructor(&#8216;alert(1)&#8217;)()]]'
date: 2019-06-01T19:50:28+00:00
author: admin
layout: revision
guid: https://syzhack.com/blog/index.php/2019/06/01/75-revision-v1/
permalink: /index.php/2019/06/01/75-revision-v1/
---
###<img class="wp-image-76 aligncenter" src="https://syzhack.com/blog/wp-content/uploads/2018/12/Googlelogo.png" alt="" width="194" height="66" /> 

### #Vulnerability type:

Stored Cross-Site Scripting

### #Author:

Măgherușan Ovidiu Teodor  
&#8212;-

### #Proof of concept:<figure id="9d65" class="graf graf--figure graf-after--p"> 

<div class="aspectRatioPlaceholder is-locked">
  <p>
  </p>
  
  <h3 id="a384" class="graf graf--h3 graf-after--p">
    #Vendor response:
  </h3>
  
  <p id="634a" class="graf graf--p graf-after--h3">
    Google provides standardized rewards for most security bugs, as described on the page for it&#8217;s <a class="markup--anchor markup--p-anchor" href="https://www.google.com/about/appsecurity/reward-program/index.html#rewards" target="_blank" rel="nofollow noopener" data-href="https://www.google.com/about/appsecurity/reward-program/index.html#rewards">vulnerability reward program</a>. In our case, a proper XSS on the mail.google.com (Mobile APP) domain will usually trigger a $5,000 bounty.
  </p>
  
  <p id="0fc4" class="graf graf--p graf-after--p">
    8 August 2017, 17:48 — I fill in the <a class="markup--anchor markup--p-anchor" href="https://www.google.com/appserve/security-bugs/new" target="_blank" rel="nofollow noopener" data-href="https://www.google.com/appserve/security-bugs/new">report form</a>.<br /> 9 August 2017, 01:06 — My report is triaged, already!<br /> 10 August 2017, 13:50 — My report is validated, bug filed.<br /> 11 August 2017, ? — Well, this is fixed.<br /> 16 August 2017, 13:50 —<img class="alignnone size-full wp-image-82" src="https://syzhack.com/blog/wp-content/uploads/2018/12/Screenshot_3.png" alt="" width="634" height="772" />
  </p>
  
  <p>
    &nbsp;
  </p>
</div></figure> 

&nbsp;

### #Hall of Fame:

https://bughunter.withgoogle.com/profile/9c53933c-4d4e-4989-b029-89e2c10290c8