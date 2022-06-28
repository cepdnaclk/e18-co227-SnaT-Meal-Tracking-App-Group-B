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

![](https://s3.amazonaws.com/img.mynetdiary.com/images/iphonex@1x.png)


## Team
-  E/18/068, Chiran Devinda, [e18068@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/368, Hirusha Uthsara, [e18368@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/030, Sathsarani Aththanayaka, [e18030@eng.pdn.ac.lk](mailto:name@email.com)

## Table of Contents
1. [Changes](#changes)
2. [Current App](#current-app)
3. [Analysis and Suggestions](#analysis-and-suggestions)
4. [Features](#features)

---

# Changes


### a) Phase 01

 * __Increase  user experience__ - Need to change  the user interface  of the  application  to increase user experience.  (example : Apply nice  theme/format)

 * __Arrangement  of  images__ - Users can take pictures  of  their meals/food and  upload to the system. These  images should  be  nicely presented as albums. 

 * __Output__  - According  to data  entered  by the  users , the application should be able to provide weekly/monthly summary output.  It gives attractive self reflection of the users.Emojis  will be used to reflect the result of output.



### b) Phase 02


* __Interact with social media__ -  Need to add a separate  functionality to post their results of the application  to social media. 

* __Process images__ -  By  processing images , System may suggest the food  type.  Users may have to confirm or  otherwise  users can select the food manually.   

* __Add Digital Nudging System__ - By setting reminders on peak meal times and sending some nutritional guidelines and healthy tips with it as messages

* __Incorporate of remote nutrition counseling facility__ - Should create a website linked to SnaT in order to take dietary advice through experts in this subject (Dieticians/ Nutritionists/ Doctors)



### c) Phase 03


* __Developing SnaT junior app__ - Should need to add some fun games which are suitable for pre-adolescents and adolescents to trigger their healthy eating patterns. 

* __Implement Software (Desktop  Application)__ - This should be developed as both an app and software as in Sri Lanka this age group mostly uses computers or laptops rather than mobile phones. 


# Current App


### a . High Level Architecture

![9acd375d-de6c-4add-959a-e34db734d65a](https://user-images.githubusercontent.com/73680106/172762386-ab954aa2-e471-409a-92e3-5312c2a4f5f5.jpg)

### b . Mobile technology ( Operating system)
* __Android Platform Application__

### c . Database
* __SQlite Database__


## Analysis and Suggestions

### a . High Level Architecture
![556e3f0a-5c4b-45c5-810a-b289f07d2340](https://user-images.githubusercontent.com/73680106/172762223-20373859-0953-4a95-87ff-67e3fa7eed9d.jpg)

### b . Mobile technology ( Operating system)
* Google's Android and Apple's iOS are operating systems used primarily in mobile technology.
* If we go only with an Android native application, we may not be able to access  this app by apple devices.
For this application , the suggestion is  to go with the hybrid approach.


### c . Database
* In general , we can have two types of databases  in mobile application development. They are remote  databases , Local databases. If you need to have data which is specific to the device , we can have a local database. Local database is stored in client side (in mobile device)
* If we have only a local database , if something happens to the  device all  the data will be missed.  Otherwise we have to have a  mechanism to back up and restore  data. 
* For this  application , it is preferred  to have a remote  database .  If we need offline synchronization, additionally we can have a local database.


# Features

### Login 
* Username -Password Login /  Signup Page
* Login with Google

### User Registration 
* Enter user’s details : Name , Birth Date , Height , Weight

### BMI calculator 
* Enter details and show the BMI value
* If the user confirms, that data should be able to save to the database.  

	     
### Maintain Meal Details 
* Select  the date (if same day , no need to select date), meal type  , the relevant food from the list (if that food is not  in the list user should be able to enter * that food to the relevant food group) and quantity according  to the suggested  unit.
 Users should be able to edit and delete data by selecting  the date.

### Maintain images  of meals
* Users should be able to select the date ,meal type and upload the images 
* Users should be able to  open the camera  from the app  and upload  the image. (optional)
Images should be shown as an attractive  gallery  . You can limit the search date  range maximum upto 1 month , if necessary.
  
### Output/Results
* Show   daily/ Monthly/weekly results according to the food groups whether they are beyond the expected range, within the expected  range or below the expected range. Note: Use Emojis.
		
### Connect  to social  media
* Users should  be able to share their  results  to social media directly from the app.

### App Notification
* If the user forgot to add  any meal for yesterday ,the application should show a notification  in the morning.  (  one user  gets  maximum one app notification per day)

### List  all  food 
* List all the food by food group  with the stansdad serving size . (Then user can find the  preferred  consumable portion of each food)  




## Links

- [Project Repository](https://github.com/cepdnaclk/{{ page.repository-name }}){:target="_blank"}
- [Project Page](https://cepdnaclk.github.io/{{ page.repository-name}}){:target="_blank"}
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
