---
title: "Web Scraping Using Selenium Python"
author: ''
date: "September 2020"
description: This is a tutorial for using Selenium Python to scrape websites
documentclass: book
geometry: margin=1.5in
github-repo: IQSS/dss-webscrape
link-citations: yes
site: bookdown::bookdown_site
biblio-style: apalike
---

# Introduction {-}

## Table of Contents {-}

In this tutorial, we first provide an overview of some foundational concepts about the world-wide-web. We then lay out some common approaches to web scraping and compare their usage. With this background, we introduce several applications that use the Selenium Python package to scrape websites.

This tutorial is organized into the following parts:  

1. Basic concepts of the world-wide-web.       
2. Comparison of some common approaches to web scraping.       
3. Use-cases for when to use the Selenium WebDriver.          
4. Illustration of how to find web elements using Selenium WebDriver.     
5. Illustration of how to fill in web forms using Selenium WebDriver.

We plan to add more applications in the near future. The content of this tutorial is a work in progress, and we are happy to receive feedback! If you find anything confusing or think the guide misses important content, please email: help@iq.harvard.edu.

## Custom Websites {-}

We decide to build custom websites for many of the examples used in this tutorial instead of scraping live websites, so that we have full control over the environment. This provides us stability—live websites are updated more often than books, and by the time you try a scraping example, it may no longer work. Also, a custom website allows us to craft examples that illustrate specific skills and avoid distractions. Finally, a live website might not appreciate us using them to learn about web scraping and try to block our scrapers. Using our own custom websites avoids these risks; however, the skills learnt in these examples can certainly still be applied to live websites. 

Below I list the name and its link for each of the custom websites we have built for this tutorial:

[static student profile webpage](https://iqssdss2020.pythonanywhere.com/tutorial/static/views/Adams.html)   
[dynamic search form webpage](https://iqssdss2020.pythonanywhere.com/tutorial/cases/search)      
[dynamic table webpage](https://iqssdss2020.pythonanywhere.com/tutorial/default/dynamic)        
[dynamic search load webpage](https://iqssdss2020.pythonanywhere.com/tutorial/casesLoad/search)          
[dynamic complete search form webpage](https://iqssdss2020.pythonanywhere.com/tutorial/form/search)            
[dynamic search form with a hidden field webpage](https://iqssdss2020.pythonanywhere.com/tutorial/formhidden/search)         

## Authors and Sources {-}

Jinjie Liu at IQSS designed the structure of the guide and created the content. Steve Worthington at IQSS helped design the structure of the guide and edited the content. We referenced the following sources when we wrote this guide:

* *Web Scraping with Python: Scrape data from any website with the power of Python*, by Richard Lawson (ISBN: 978-1782164364)
* *Web Scraping with Python: Collecting Data From the Modern Web*, by Ryan Mitchell (ISBN: 978-1491910276)
* *Hands-on Web Scraping with Python: Perform advanced scraping operations using various Python libraries and tools such as Selenium, Regex, and others*, by Anish Chapagain (ISBN: 978-1789533392)
* *Learning Selenium Testing Tools with Python: A practical guide on automated web testing with Selenium using Python*, by Unmesh Gundecha (ISBN: 978-1783983506)
