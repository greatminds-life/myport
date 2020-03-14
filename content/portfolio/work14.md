+++
date = "2016-11-05T01:25:22+05:30"
title = "Bloomberg Mobile Alert Catcher"
draft = false
image = "img/portfolio/AC_hero.png"
showonlyimage = false
weight = 4
+++

UX design / Requirement Gathering / Wireframe / Workflow / Prototype
<!--more-->

#### Background
Bloomberg terminal provides more than 20,000 functions to allow financial professionals to look up relevant and timely financial information. Alert catcher is one of the offerings which notifies users with market, news and economic event alerts when specified conditions are met. Once you set alert conditions for those type of alerts, you will get stream of alerts feeds on your mobile, but there is no way you can create new alert conditions on mobile yet. This could only be configured via desktop interface, and there has been growing needs that users want to customize this feature on mobile as well. Starting with market alerts support, we plan to take phased approach to tackle three different alert types in order.

![ac1][1]
Markets, News, Economic alerts supported on Bloomberg terminal

#### What to support on mobile?
After we decided to support market alerts first on mobile, the next thing is to identify core features we need to scale from desktop to mobile. First we wanted to get the full picture of desktop functinalities by going through each criteria or options we can configure to create market alert then tried to identify criteria and options to be supported on mobile with product owners and developers. We were able to create the following list of user stories for mobile experience. 

* I want to manage(create/edit/delete) market alerts on mobile
* I want to turn on/off market alerts created from desktop
* I want to create market alert from security page
* I want to set notifications of market, eco and news alerts on mobile

![ac2][2]
Markets, Economic events, news alerts supported on Bloomberg professional mobile

#### Designing flows for managing alerts
Based on the existing navigation framework of mobile alert catcher, one of the key requirement from product owner was to provide multiple entry point of creating market alerts wherever makes sense to support. One of them is on the screen where you see market alerts feed - where you see content, you can control the feed of content. Another entry point is on security page where you see market price detail information of specific asset class. Finally, under market alerts settings page, we added entry to create market alerts. In order to capture these, we have created a flow diagram to show the relationship among different screen states.
After designing workflows, created individual key screens for each state and put them into wireframe flows to elaborate user stories and requirements captured in the earlier phases.

![ac3][3]
Create and edit a market alert from 3 difference screens

#### Workflow : Create an alert from market alerts and settings
![ac4][4]

#### Workflow : Create an alert from security screen
![ac5][5]

#### Workflow : From alert catcher settings to market alerts
![ac6][6]

#### Editing an alert
![ac7][7]

#### Workflow : Viewing a terminal created alert
![ac8][8]

#### Take away
Since terminal created alerts cannot be edited on mobile, it was difficult to differentiate terminal created vs mobile created alerts. For now, it can be distinguished only when user opens an alert, it would have been better if we can indicate the difference on the alerts list.
Creating an alert from security screen can also be improved by providing conditional creat flow - when user tries to create an alert for a security already has existing alert(s) associated, we could prompt users to either a) edit existing alerts or b) create brand new alert with different set of criteria.
Since we put an entry point to create an alert from security page, it would make sense to add an entry to the already created alert(s) from the security page so that users can intuitively go to security page if they want to edit the existing alerts.

[1]: /img/portfolio/AC1.png
[2]: /img/portfolio/AC2.png
[3]: /img/portfolio/AC3.jpg
[4]: /img/portfolio/AC4.jpg
[5]: /img/portfolio/AC5.jpg
[6]: /img/portfolio/AC6.jpg
[7]: /img/portfolio/AC7.jpg
[8]: /img/portfolio/AC8.jpg




