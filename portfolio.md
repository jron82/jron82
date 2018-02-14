---
layout: post
title: Portfolio
---


Here is a list of the projects I've worked on in no particular order.

## AMI Campus

![AMI Campus]({{ "/img/Banner_Apostolic_Network_SM.png" | absolute_url }})


AMI Campus is an on-demand e-learning website is written in PHP that I refactored. I worked with another developer on this project but I was the lead developer.

I started by forking the codebase of a sister website. The flaws of that app was that database access calls, presentation, and business logic were all mixed together.

Furthermore, all of the code was procedural and everything was in one giant file.

I broke that file apart and created sensible objects with single responsibilities and as extracted views from the business logic.

The authentication was updated and a password recovery feature added. Then we completely we worked the payment to cater for international students.

All along the way acceptance tests were added.

## AMI Bookshop

![AMI Bookshop]({{ "/img/gmr_pub_banner.jpg" | absolute_url }})

AMI Bookshop is an e-commerce storefront written in PHP/MySQL that processes orders, as well as general -e-commerce functionality like sales discounts and customer specific email marketing campaigns.

I came to the project after it had already been going for a few years so was mostly refactoring, adding new features and security.

The main work was in cleaning up the codebase to be extensible.

## AMI Mailing System

AMI Mailing system is an email marketing and email course management system written in PHP and MySQL.

Like AMI Bookshop, my main job was refactoring and adding new features. I switched out the email delivery transport, added proper email authentication (SPF, DKIM, DMARC), added double opt-in and opt out, and updated the admin backend.

I also added better logging and exception handling.