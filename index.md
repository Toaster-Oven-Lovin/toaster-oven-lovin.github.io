## Overview

The problem: Many college students have limited kitchen resources, limited cooking skills, limited time, limited access to grocery stores, and no access to creative recipes that respect these constraints. As a result, college students spend money to eat out, or eat non-healthy foods at fast food places or through vending machines.

The solution: Healthy Manoa creates a way for students (on-campus or off) to learn and share recipes that:
* Can be made using minimal kitchen facilities (at a minimum, a toaster oven).
* Can be made out of ingredients that are available within walking distance of UH.
* Suit local taste sensibilities.
* Can be filtered via dietary restrictions (gluten-free, vegan, etc).
* Have an estimated cost per serving.
* Has an estimated number of servings per recipe.
* Has an estimate of how long it takes to make.

## Links to:
- [Github Organization](https://github.com/healthy-manoa)
- [Project Milestone 1](https://github.com/healthy-manoa/project/projects/1)
- [Project Milestone 2](https://github.com/healthy-manoa/project/projects/2)
- [Project Milestone 3](https://github.com/healthy-manoa/project/projects/3)
- [Galaxy Page](https://healthymanoa.meteorapp.com)
- [Project Board](https://github.com/healthy-manoa/project/projects/2)

## Team Members
* Rexter Delos-Santos
* Timothy Nicdao
* Weixiao Hu
* Haochen Wang

## Developer Guide

* Install Meteor on <a href="https://www.meteor.com/install">https://www.meteor.com/install</a> and use as a base website for develop. 
```
meteor npm install
```
* Running Meteor on local computer and editing and developing the website with code language (JavaScript, UI, React).
```
meteor npm run start
```

```
C:\Users\user\Documents\GitHub\project\app>meteor npm run start

> meteor-application-template-react@ start C:\Users\57466\Documents\GitHub\project\app
> meteor --no-release-check --settings ../config/settings.development.json

[[[[[ C:\Users\user\Documents\GitHub\project\app ]]]]]

=> Started proxy.
=> Started MongoDB.
W20191217-15:04:17.425(-10)? (STDERR) Note: you are using a pure-JavaScript implementation of bcrypt.
W20191217-15:04:17.741(-10)? (STDERR) While this implementation will work correctly, it is known to be
W20191217-15:04:17.742(-10)? (STDERR) approximately three times slower than the native implementation.
W20191217-15:04:17.742(-10)? (STDERR) In order to use the native implementation instead, run
W20191217-15:04:17.742(-10)? (STDERR)
W20191217-15:04:17.743(-10)? (STDERR)   meteor npm install --save bcrypt
W20191217-15:04:17.743(-10)? (STDERR)
W20191217-15:04:17.743(-10)? (STDERR) in the root directory of your application.
I20191217-15:04:18.232(-10)? Creating the default user(s)
I20191217-15:04:18.233(-10)?   Creating user admin@foo.com.
I20191217-15:04:18.456(-10)?   Creating user vendor@foo.com.
I20191217-15:04:18.657(-10)?   Creating user john@foo.com.
I20191217-15:04:18.852(-10)?   Creating user kyle@foo.com.
I20191217-15:04:19.058(-10)? Creating default data.
I20191217-15:04:19.059(-10)?   Adding: Basket (john@foo.com)
I20191217-15:04:19.085(-10)?   Adding: Bicycle (john@foo.com)
I20191217-15:04:19.089(-10)?   Adding: Banana (admin@foo.com)
I20191217-15:04:19.091(-10)?   Adding: Boogie Board (admin@foo.com)
I20191217-15:04:19.093(-10)? Creating default data.
I20191217-15:04:19.094(-10)?   Adding: Sample Vendor (vendor@foo.com)
I20191217-15:04:19.114(-10)?   Adding: Sample Vendor (vendor@foo.com)
I20191217-15:04:19.116(-10)?   Adding: Sample Vendor (vendor@foo.com)
I20191217-15:04:19.118(-10)?   Adding: Sample Vendor (vendor@foo.com)
I20191217-15:04:19.120(-10)?   Adding: Sample Vendor (vendor@foo.com)
I20191217-15:04:19.123(-10)?   Adding: Sample Vendor (vendor@foo.com)
I20191217-15:04:19.126(-10)? Creating default recipes.
I20191217-15:04:19.127(-10)?  Adding: Fried Rice (john@foo.com)
I20191217-15:04:19.150(-10)?  Adding: Spam Musubi (kyle@foo.com)
I20191217-15:04:19.155(-10)? Creating default vendors.
I20191217-15:04:19.157(-10)?  Adding: Longs Drugs
I20191217-15:04:19.178(-10)?  Adding: SafeWay
I20191217-15:04:19.180(-10)?  Adding: Walmart
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.
```

* All development of the website is push to and storage at Github. 
* Deploy the website through Galaxy from Github

## User Guide
* Access the Healthy Manoa website, you will start at the home page (landing page).
* Without signing in, you can see the vendors near UH as well as the full list of all the recipes on the site.
* Search bar in home page will search everything (vendors and recipes) on the site.
* If you don't have account, you must sign up for account with email and password (As student or vendor).
* Signing in allows you to create your own profile, upload recipes, and edited recipes.
* Signing in as vendor, you can post your business as a vendor,and create and manage inventories as well.
* To test the admin functions, log in with the username: admin@foo.com and the password: changeme

## Landing Page
The home page will welcome the user to the Healthy Manoa with search bar.

<img class="ui floated rounded image" src="/images/landing.PNG">

## About Us Page
The About Us page gives brief information on app and organization. Provides link to this page.

<img class="ui floated rounded image" src="/images/About.PNG">

## Vendor Page
List of all vendors near UH.

<img class="ui floated rounded image" src="/images/Vendor page.PNG"> 

## Recipes Page
List of all recipes.

<img class="ui floated rounded image" src="/images/Recipes page.PNG">

## Signin/Sign up Page
<img class="ui floated rounded image" src="/images/signin.PNG">
<img class="ui floated rounded image" src="/images/signup.PNG">
<img class="ui floated rounded image" src="/images/edit password.PNG">

## Add/Edit Recipe
Page to add recipe to recipe list.

<img class="ui floated rounded image" src="/images/Add Recipe page.PNG">
<img class="ui floated rounded image" src="/images/Edit Recipe page.PNG">

## Inventory Page
Page for vendors to add inventory.

<img class="ui floated rounded image" src="/images/Inventory page.PNG">

## Add/Edit Inventory
<img class="ui floated rounded image" src="/images/add inventory.PNG">
<img class="ui floated rounded image" src="/images/edit inventory.PNG">

## Add/Edit Vendor

<img class="ui floated rounded image" src="/images/add vendor.PNG">
<img class="ui floated rounded image" src="/images/edit vendor.PNG">

## Community Feedback

* Background of inventory could be a different picture to match the theme of the site
* Search bar can should be centered along with the button near it
* Too much options at the top of the page, incorporate buttons to their respective pages instead
* Front page looks welcoming 
* A map or link to google maps can help students figure out how to get to the stores

  



