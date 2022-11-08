---
title: Build A Weather App
draft: false
date: 2022-11-01T20:00:59.371Z
publishdate: 2022-11-01T21:00:10.686Z
host: Girls Who Code at UNCC
image: /Girls-Who-Code-at-UNCC/images/untitled-design-35-.png
event_type: Technical
event_topic:
  - weatherappwithjavascript
year: "2022"
semester:
  - Fall
visibleInCMS: true
---
T﻿hank you to everyone joining the Build A Weather app event we held last week! Still want to build your own?? No worries down below we have further details about our code documentation and the link to the full code as well. Feel free to email at girlswhocodeuncc@gmail.com if you need any help. Thank you and enjoy! :)



## **C﻿ode Files Breakdown:**

* 3 file components to the app: html, css, and javascript
* Html is a markup language that is used to make web pages and add text, image, and other elements to websites
* CSS is a style sheet language and allows for styling of the elements on websites, including styles for font size and text alignment
* Javascript is what will control the elements on the website; for example, js allows you to click a button on a website and receive a response from that click. It is a programming language, unlike html and css, meaning it is supposed to produce various outputs and contains instructions for those outputs



#### **index.html file:**

* Explain comments above <head> element
* First link element will connect html file to css file
* Content of <body> element represents main content of website; add text, headers, images, etc here
* * <div> element just represents a division of the file
  * Within <div> tag can add elements such as regular text or headings
  * Pay attention to class/id keywords
* Run file now to view output
* No information about weather shows because we have not coded in javascript file yet
* Content is not styled either



#### **style1.css file:**

* Css file allows for styling of elements on a website, works in conjunction with html file
* Keywords added before curly brackets are called selectors
* Hover over each property to understand what it does (pretty self explanatory :) )
* Edit name of file to be style.css
* Rerun code; show how now that the css file name matches what is in the html file, the html file can communicate with the css file and vice versa



#### **script.js file:**

* How to get weather data? Use API from website into our app
* * API is a medium between server (website) and client (users on our app) to serve data based on client’s request
* We need API key from this website <https://openweathermap.org/>
* * Create account
  * Click on API on top menu 
  * Current weather data - subscribe
  * Select free option “get API key”
  * Find API key in “My API keys” on top (will be different for everyone)
* We can use the unique API key to view the json file by adding the name of our selected city and the API key to the url at the beginning of the js file

**[L﻿ink to the full code](https://replit.com/@LoloAboufoul/WeatherAppGWCComplete)**.