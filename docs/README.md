---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e18-co227-SnaT-Meal-Tracking-App-Group-B
title: SnaT Meal Tracking App
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# SnaT Meal Tracking App

---

## Team
-  E/18/068, Chiran Devinda, [e18068@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/368, Hirusha Uthsara, [e18368@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/030, Sathsarani Aththanayaka, [e18030@eng.pdn.ac.lk](mailto:name@email.com)

## Table of Contents
1. [Introduction](#introduction)
2. [Technology Stack](#technology-stack)
3. [Solution Architecture](#solution-architecture)
4. [Features](#features)
5. [Links](#links)

---

# Introduction

This is a multi-platformed application to track user's Meals in order to give feedback about state of nutrition consumption of the user over a some time period.This application is based on SriLankan food culture and it features comprehensive food database.

The app contains user-friendly interfaces that allows user to have great experience. The home page shows the list of main course meals such as breakfast,lunch and dinner and also snaks.Let's think you want to add your lunch, you can click on that button and add the meal with the sizes.In addition, there is a feature which facilitate to take picture of your food and save it into a gallery with respect to the relavant date and also the respective course meal. User can navigate through the app bar and find more features that are offered from this app.This app generate attractive graphs which are showing the state of nutrition consumption of the user over a specific time period.

<p align="center">
  <img width="500" src="https://aaps.ca/wp-content/uploads/Aug-6-sport-and-nutrition-training.jpg" alt="Taking picture of food">
</p>






# Technology Stack

<img src="https://user-images.githubusercontent.com/73680106/176659070-eb03a351-84ab-4c7c-b928-6089b401a6a2.png" alt="tech stack" width="600"/>

- [Flutter](https://flutter.dev/)
- [Dart](https://dart.dev/)
- [Firestore](https://firebase.google.com/products/firestore?gclid=CjwKCAjwkYGVBhArEiwA4sZLuKu5oA_7xzoBYUbQzs9VdFiaHN1tmOt0Oc_pEWFD1jdu-QmmLyhVrRoCK-wQAvD_BwE&gclsrc=aw.ds)


# Solution Architecture

<p align="center">
  <img width="900" src="https://user-images.githubusercontent.com/73680106/176661576-ca4a83ce-e40a-40f3-ac42-a2d733c445e0.png" alt="drawing">
</p>


<p align="center">
  <img width="900" src="https://user-images.githubusercontent.com/73664068/176867110-5b655532-0b7f-4265-8002-f80434fbffec.PNG" alt="storage">
</p>


# Features

### Login 
This app provide two sign in methods. User can first sign up using an email and a password and then they can proceed with sign in.Other than that user can simply use google sign in method.

How does it work?

To sign in, first the app should get authentication credentials from user. For this app credential can be email and password or the oAuth token from google. Then the app pass these credential to Firebase Authentication SDK.After that it will verify those credentials and return respose to the app.Now, the app can access the user's basic profile information.

<img src="https://user-images.githubusercontent.com/73664068/176868525-1bbaa1f2-7c06-456c-ac37-6b295261776f.jpg" width="300" />


### User Registration 
For the registration purposes, the user is required to enter username, date of birth, gender, height and weight.This details use for other features.

Ex:- BMI calculator

<img src="https://user-images.githubusercontent.com/73664068/176868581-04c3f756-8d95-4573-b20d-5f61ceefc771.jpg" width="300" /> 

### BMI calculator 
* Enter details and show the BMI value
* If the user confirms, that data should be able to save to the database.  

<img src="https://user-images.githubusercontent.com/73664068/176869561-27bf16ee-6508-4773-9ebb-5db62918a562.jpg" width="300" /> 
	     
### Maintain Meal Details 
* Select  the date (if same day , no need to select date), meal type  , the relevant food from the list (if that food is not  in the list user should be able to enter * that food to the relevant food group) and quantity according  to the suggested  unit.
 Users should be able to edit and delete data by selecting  the date.
 
<img src="https://user-images.githubusercontent.com/73664068/176869732-eb5997a2-efca-4948-9df4-6e2e8d3b6571.jpg" width="300" /> 
 

### Maintain images  of meals
* Users should be able to select the date ,meal type and upload the images 
* Users should be able to  open the camera  from the app  and upload  the image. (optional)
Images should be shown as an attractive  gallery  . You can limit the search date  range maximum upto 1 month , if necessary.

<img src="https://user-images.githubusercontent.com/73664068/176869895-720b7bd8-c395-434f-9bea-105afff19a1f.jpg" width="300" /> 
  
### Output/Results
* Show   daily/ Monthly/weekly results according to the food groups whether they are beyond the expected range, within the expected  range or below the expected range. Note: Use Emojis.
		
### Connect  to social  media
* Users should  be able to share their  results  to social media directly from the app.

### App Notification
* If the user forgot to add  any meal for yesterday ,the application should show a notification  in the morning.  (  one user  gets  maximum one app notification per day)

<img src="https://user-images.githubusercontent.com/73664068/176871011-41fc0255-499b-4fe1-96ec-f6e31af034df.jpg" width="300" /> 

### Language Translation 
* App supports English(US), Sinhala & Tamil




<video src='https://user-images.githubusercontent.com/73680106/176605718-151da18b-c280-426a-8ec4-26e54d5f44ea.mp4' width=900/>

## Links

- [Project Repository](https://github.com/cepdnaclk/{{ page.repository-name }}){:target="_blank"}
- [Project Page](https://cepdnaclk.github.io/{{ page.repository-name}}){:target="_blank"}
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
