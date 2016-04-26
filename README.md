# Alexa

HeavyWater Codeathon: Virtual Assistant

Based on **Alexa Voice Service** and __Alexa Skills Kit__

+ Liang Peng
+ University of Pennsylvania

# Video Demo
[Video Link](https://vimeo.com/164201800)

# How to Run
* Make sure following environments are installed:
 * Apache Maven
 * Java 8
* Double click Service.bat
* Double click Client.bat
* DO NOT click OK! Copy the url in the popped up window (starting with https://localhost:3000) and paste it in a browser and enter. If you are warned with security issue, just select ignore and go ahead.
* Click OK.
* Now you can talk with Alexa after clicking "start listening".

# Commands
* Try speaking following commands:
 * HeavyWater
 * What can you do?
 * I have a file to upload. (e.g. file 1)
 * Process the file. (e.g. file 2)
 * What's the largest deposit?
 * Report the types of documents.

# Live Cards
Open [http://echo.amazon.com](http://echo.amazon.com) in browser to see the conversation records.

# Implementation Outline
* Set up __Amazon AWS__ account
* Set up __Amazon Developer__ account
* Create a __Security Profile__ in developer console
* Set up __Login with Amazon__ tab in developer console
* Create a __Alexa Voice Service Device__ in developer console
* Download __Alexa Sample App__ and generate __self-certified credentials__ using __OpenSSL__
* Create __Lambda__ and select Java in AWS console
* Coding command handling logic, build code and upload to Lambda in AWS console
* Create a new __Alexa Skill__ and customize __Voice Schema__ in developer console
* Run sample app and test
