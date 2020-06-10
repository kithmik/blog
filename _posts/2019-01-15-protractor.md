---
layout: post
title:  "Protractor Automation Tool"
author: kithmi
categories: [ Testing, Automation ]
tags: [automation, protractor]
image: assets/images/protractor1.png
description: "Protractor Automation Testing Tool"
featured: true
hidden: false
rating: 4.0
---

# Protractor Automation Tool

The protractor is end-to-end test automation for angular.js application. So it's already an inbuilt framework for mainly angular.js application. It is built on top of the web driver js protocol. Since Protractor works on top of the js protocol it can handle the js application quite easily.

Nowadays why people are starting using Protractor for Angular JS application. Because it has some additional locator strategies. so if you have worked on selenium or any other automation
tools they have a standard locator like ID name XPath CSS. But this protractor already has some additional locators like ng-model by adding a few more additional locators. 
Also, the most important point of The protractor is you don't have to add the wait statements or you
don't have to use sleep statements.
 
### Installing and running part of the protractor 
 
Protractor needs two files to run,  

             spec file 
             configuration file 
   
##### How to install Protractor globally 
 
npm install -g protractor 


This will install protractor, and web driver-manager. The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running and need to make sure the web driver is up to date.

Webdriver-manager update - update web driver
webdriver-manager start - start the web driver

Now you can run the test using protractor conf.js
