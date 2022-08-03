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
  <img width="700" src="https://user-images.githubusercontent.com/73664068/176867110-5b655532-0b7f-4265-8002-f80434fbffec.PNG" alt="storage">
</p>





# Features
<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/73664068/182664739-b7fc69bb-c3c8-4085-892c-3c9e631ad6ce.jpg" alt="Front">
</p>




### Login 
This app provide two sign in methods. User can first sign up using an email and a password and then they can proceed with sign in.Other than that user can simply use google sign in method.

How does it work?

To sign in, first the app should get authentication credentials from user. For this app credential can be email and password or the oAuth token from google. Then the app pass these credential to Firebase Authentication SDK.After that it will verify those credentials and return respose to the app.Now, the app can access the user's basic profile information.


<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/73664068/182669513-f741add1-8e42-4ca0-8394-94987c50a190.jpg" alt="SignIn">
</p>

### User Registration 
For the registration purposes, the user is required to enter username, date of birth, gender, height and weight.This details use for other features.

Ex:- BMI calculator


<p align="center">
  <img width="250" src="https://user-images.githubusercontent.com/73664068/182665643-8521edfa-9c39-4d42-a8e3-dcf8150f9cbd.jpg" alt="Registration">
</p>

### BMI calculator 
* Show the BMI value of the user.
* It gives additional feedback about BMI using gender and age.


<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/73664068/182666194-0e0a3474-f05d-473d-91bc-1a9443ebf1e2.jpg" alt="BMI">
</p>


### Maintain images  of meals
* Users can select the date ,meal type and upload the images.
* Users can open the camera  from the app  and upload  the image. These images store in cloud space.
* The app can load the according to the selected date range and here is a  limit the search date range maximum upto 1 week
* The app loads images from the cloud storage according to the selected meal time 
* The images will show with grid view and list view
* User will be able to delete the images through gallery
* There will have small description about the imagesin gallery after selecta image


<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/73664068/182666436-1ea56bc5-dc2c-470d-85e0-55249699f4bd.jpg" alt="mealGallery">
</p>

  

### App Notification
* If user forgot to add a meal, this will pop up a notification.

<p align="center">
  <img width="250" src="https://user-images.githubusercontent.com/73664068/182671840-6a7dad07-19dc-4b61-8d4c-17b108714d0a.jpg" alt="Notification">
</p>




### Language Translation 
* App supports English(US), Sinhala & Tamil.

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/73664068/182672037-92b742f2-b7ae-42a2-ace4-ec98da226946.jpg" alt="Translation">
</p>


## Links

- [Project Repository](https://github.com/cepdnaclk/SnaT-meal-tracking-app)
- [Project Page](https://cepdnaclk.github.io/e18-co227-SnaT-Meal-Tracking-App-Group-B/)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
