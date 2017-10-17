ICS 325 Fall 2017 - Assignment 7
=========================

Purpose
-------
* Learn how JavaScript and PHP can interact via JSON.
* Learn the basics of JSON.
* Learn the basics of asynchronous browser requests (AJAX).

Resources and Examples
----------------------
* w3cschools [JSON examples](https://www.w3schools.com/js/js_json_intro.asp).

Collaboration
-------------
You can work with 1 or 2 other students on this assignment.  Make sure to mention who you worked with when you submit your assignment in D2L.

Prerequisites
-------------
Use git to clone or simply [download](https://github.com/MetroState-ICS-325-Fall-2017/ICS-325-F2017-Assignment_7/archive/master.zip) this example assignment 7 code repo from github.com to your computer.  Then in PhpStorm, use `File->Open Directory` and select your local repo.

Instructions
------------
### Instructions to set up the code to run


Next you need to set up PhpStorm.  We will be using the built-in PHP CGI server for this assignment.  To do so, first make sure you have the git repo open in PhpStorm by using the Open Directory menu item under File in PhpStorm (`File->Open Directory`).  Next go to `Run->Edit Configurations...` Click the green `+` to create a new configuration.  Select `PHP Built-in Web Server`.  Change the name to `Cookies and Sessions Lab`.  Leave host as `localhost`.  Set the port to `8080`.  Set the `Document root` to your git repo directory by clicking the `...` button next to the field and using the file chooser to select it.  In the top right of the window there is a check box labled `Single instance only`, click on it to check it.  If there is a red ! icon near the bottom right of the window, click the `Fix` button and specify your PHP interpreter.  Once done, click `Ok` to exit the Edit Configurations window.  Next hit the green run button to start the PHP CGI web server.  Then go to your web browser and enter this url [http://localhost:8080/orderform_json.html](http://localhost:8080/orderform_json.html).  

`orderform_json.html` is broken down into 4 sections:
* The Bob's Auto Parts HTML form
* JSON sent to PHP from JavaScript: The JSON string that PHP will receive from JavaScript.
* JSON received from PHP to JavaScript: The JSON string that PHP sent to JavaScript.
* Order Result (JSON parsed from PHP by JavaScript): The order results output that would normally be shown to the user.  A random number is generated for the order number.

### Assignment Work
You should first read the w3cschools [JSON examples](https://www.w3schools.com/js/js_json_intro.asp).  Read all sections except for "JSON JSONP".  Then experiment with the example code I've provided.  Read the code and all the code comments to gain an understanding of the code.

For the graded portion of the assignment, in D2L there is a Microsoft Word document with the questions you need to answer.  There is no coding required for this assignment.
