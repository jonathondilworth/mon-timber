# README.md | Mon Timber Example & Proposal

The current web design @ [Mon Timber](http://www.montimber.co.uk/) is somewhat outdated. Furthermore, the shop has been implemented inappropriately, such that it no longer works.

A brief report has been compiled against SEO examination and the main issues associated with their current website are:

1. No SSL Certificate (Effects Google Ranking)
2. Fairly slow mobile load pages (Fixable with AMP)
3. Low to Average Domain Authority (We'll look to fix this by adding more content that dynamically changes)

Please see the following Website Design For Mon Timber 

[Here, at https://mon.dilworth.me/](https://mon.dilworth.me/)

*bare in mind the text is simply there to placehold currently.*

If the client is happy, I will continue to use [Laravel-MVC](https://laravel.com/), [Nova](https://nova.laravel.com/) and [Cashier](https://laravel.com/docs/8.x/billing), or: [WordPress](https://wordpress.com/) and [Magento](https://magento.com/).

If we're all happy thus far, we can continue soon!

-

# Mon Timber: Client Requirements & Misc Info

### 1. Introduction

This document serves three purposes. Firstly, the document outlines some **brief questions** in relation as to how exactly Mon Timber *(referred to from here on as: the client)* would like their website presenting to their customers. Secondly, as an experienced software engineer and web developer<sup><a href="#fn1">1</a></sup>, it is my duty to provide various options and the best possible advice to any potential client (whether it be for a favour, or as a paid piece of work). Thus, this is what I intend on doing. Finally, a brief report is compiled focusing on the clients current website. This report includes: the sitemap, a proposed sitemap, some developer notes, suggestions, general observations, my professional opinion and some references (plus footnotes).

### 2. Brief Questions In Relation To How The Client Would Like To Present Their Website

**Please think about the following as you consider the questions:**

When you visit a website, first of all, how did you find that website? Was it through FaceBook? Was it through a search engine? Was it through word of mouth? Secondly, how do you judge a website (and thus, the company that is hosting it as their shopfront) - how much time to you take before you decide whether it is a reputable company or not? How fast do you make purchase decisions? How fast does it take (and what does it take) for you to decide against making an inquiry?

### 2.1 Please See The Following Brief Questions

1. How much and what exact information would you like your customers to initially obtain (on first glance) about your company? 
	* *Remember: it takes approximately 15 seconds for somebody to leave your website if they're not satisfied [[1]](#1) by it.*
2. What do you believe are the best qualities of your company and how do you think you can best convey these qualities to all prospective customers?
	* For example: The <a href="https://ewpeng.co.uk">website I Built for EWP</a> shows a number of hero images as part of a slide show before you scroll down the page. In addition, overlays text on top. This serves as a very quick summary of what the company does, providing the user with two things: a presentable photograph of some potential work and information about whether the company provides the types of service they're looking for. *Note: yes, we did take all the photographs, even the drone photography.*
	* However, we could have emphasised testimonials instead. Essentially the question boils down to **where does your business hold he most merit?**
3. How do you currently direct potential customers to your website?
	* For Example: Word of Mouth, SEO, Social Media, etc.
4. What is are your:
	* Premium Services (Top Priority)
	* Standard Jobs (Medium Priority)
	* Loss Leaders (Bottom Priority)
5. What sort of timeframe do you need this project completing within? The more time I have to work on developing the website, the better. However, there are various options depending on how you would like to proceed with this question, these options are outlined within the 'My Professional Opinion' section.

### 3. Current Sitemap

* Home
* <small>Shop - Different Website - Hosted Somewhere Else</small>
* Contact Us
* Decking
 	* <small>Links to Shop (Another Website)</small>
 		* <small>Shop Softwood Decking Products</small>
 		* <small>Shop Composite Decking Products</small>
 		* <small>Shop Hardwork Decking Products</small>
* Engineered Timber
	* Trusses
	* I Beam Joints [+ Download Technical Guide]
	* Posi Joists
* Joinery
* Flooring
	* Real Wood Engineered Floors
	* Solid Wood Floors
* Find Us & Contact
* Footer Based Links
 	* FAQs
  	* Contact
	* T&Cs
	* FSC/PEFC Certificates
	* GDPR Policy
	* Facebook Link
	* LinkedIn Link
	* Instagram Link


### 4. Proposed Sitemap

I'm going to leave this for now until I understand more about the client requirements. The only thing I will say is, the sitemap needs to be reduced in complexity, see the following reference [[2]](#2):

Min Chen, <br />
Improving website structure through reducing information overload, <br />
Decision Support Systems, <br />
Volume 110, <br />
2018, <br />
Pages 84-94, <br />
ISSN 0167-9236, <br />
<https://doi.org/10.1016/j.dss.2018.03.009.>

### 5. Notes

* MonTimber.online appears to be the shop-front for MonTimber
* Links on MonTimber.online (such as FAQs and AboutUs, on the footer) link to Bad Request (5xx Error, usually something like a Bad Gateway request, possibly due to misconfigured server permissions on individual files, or folders).
* Although MonTimber.online and MonTimber.co.uk appear to use the same template, they seem to be different websites:
	* MonTimber.online has an SSL certificate.
	* MonTimber.co.uk does not
	* PING montimber.online (185.79.109.83): 56 data bytes
	* PING montimber.co.uk (162.159.129.35): 56 data bytes
* (c) 2017 SiteMaker Software Ltd. This appears to be the software / company used to create their current website.
* *Note: We'll add more to this over time.*

### 6. Suggestions

1. Instead of having MonTimber.online as a store, use a subdomain name (implement the following DNS records: either a CNAME record at: store.montimber.co.uk, or shop.montimber.co.uk), as this is more typical and will likely be 'looked upon more favourably' by search engine indexers (crawlers).
2. Reduce Sitemap.
3. *Note: We'll add more to this over time.*

### 7. My Observations / Professional Opinion

* I had noticed that the 'Shop' wasn't working about a week or so ago, there appears to be someone else working on their website too, I wouldn't necessarily want to interfere with somebody else's work.
* If they're happy with what they've got and they're happy with somebody else doing the work (and, to be clear: if this website was to be re-vamped and 'modernised' - there would be a **large** amount of work involved), then I see no reason to duplicate efforts.
* However, I would suggest making some changes and, if I'm completely honest, revamping the entire website; however, that is not my call.
* As mentioned, I am willing to do a considerable amount of work for free, so long as it benefits all parties involved. However, I see no reason to do work if it is not deemed as necessary by the client (if they don't want me to, basically).
* All I can say and or do is provide my professional opinion
* What do I mean by professional? Six to eight years of website and web application development. Five of those years have been 'off my own back', two of those years have been under the employment of a professional company and one of those years has been as a freelance agent.
* My opinion is: the website is generally quite outdated. There is a list of newer technologies (front-end and back-end) which are back-wards compatible with older web browsers which I would personally opt to use <span id="sup1"><sup>[2](#fn2)</sup></span>.
* It may, however, be easier and save some time to implement the website using a new-age website builder, plus a store solution such as Shopify. Could be completed in a number of weeks. (Easiest, shortest, but incurring subscription fees).
* An alternative would be WordPress and Magento (although, I don't have very much to say about Magento, if you can find me a developer who enjoys working with it, I would very much be supprised). Full package could probably be rolled out in about a month. (Medium difficulty, would need maintaining and upgrading in the future).
* Yet another alternative is to take the 'professional' approach and to use the correct tooling for the job, only, this type of job would take (it's difficult to provide a time estimate), but a basic website with no store (but built professionally): a month, or so. If you also wanted a store built into that, you're looking at an additional month. Rule of thumb: always double estimates. Totals: 2 - 4 months. (Hardest, longest, built to stand the test the time).
* *Note: We'll add more to this over time.*

### References

<a href="#1" id="1">[1]</a>
<https://www.bettertechtips.com/web/the-15-second-rule-10-reasons-why-users-leave-a-website/>

<a href="#2" id="2">[2]</a>
Min Chen, <br />
Improving website structure through reducing information overload, <br />
Decision Support Systems, <br />
Volume 110, <br />
2018, <br />
Pages 84-94, <br />
ISSN 0167-9236, <br />
<https://doi.org/10.1016/j.dss.2018.03.009.>


### Footnotes

<a href="#fn1" id="fn1">1.</a> You can view my CV here: <a href="www.linkedin.com/in/jondilworth">www.linkedin.com/in/jondilworth</a>

<a href="#sup1" id="fn2">2.</a> Firstly, if this was a light (quick to deploy) project, I would likely use a [Linux](https://www.linuxfoundation.org/), [NGINX](https://www.nginx.com/), [MySQL](https://www.mysql.com/), [PHP](https://www.php.net/) ([LEMP](https://lemp.io/) Stack) with a [WordPress](https://wordpress.com/) installation. Given my experience with WordPress, whilst it is very much able to handle a job such as this, it can be particularly horrible to deal with when under **heavy** customisation; however, if the client wishes to use WordPress, as they may be familiar with it, that is completely fine. As it stands, I would likely use a technology stack I am much more well versed in (and is considered to be much better for larger scale websites, for example, ones with in-built stores). I would still use a LEMP stack, however, I would be looking to use a Model-View-Controller Framework called [Laravel](https://laravel.com/). In addition and would likely choose to use the [Stripe SDK](https://stripe.com/docs/api?lang=php).