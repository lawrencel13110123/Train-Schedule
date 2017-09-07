# Train-Schedule
----------
## Table of Contents 
1. [Overview](#overview)
2. [Technologies](#technologies)
3. [Local Installation](#installation)
4. [App Display](#display)

<a name="overview"></a>
## Overview 

Train-Schedule allows user to add and remove trains from their train schedule by using firebase as database. 

<a name="technologies"></a>
## Technologies

- Bootstrap 
- Firebase 

<a name="installation"></a>
## Local Installation

### Step 1: Git Clone

Clone Train-Schedule to your local git repo like the following:

> git clone https://github.com/lawrencel13110123/Train-Schedule

The Train-Schedule project and its files should now be in your project folder.

### Step 2: Set up firebase 

```javascript 
	 var config = {
	    apiKey: "AIzaSyDZ7E1aV4O2DO8J-TaFYleLbqMiUMH_qDg",
	    authDomain: "bootcamp-homework.firebaseapp.com",
	    databaseURL: "https://bootcamp-homework.firebaseio.com",
	    projectId: "bootcamp-homework",
	    storageBucket: "bootcamp-homework.appspot.com",
	    messagingSenderId: "455330930046"
	  };

	  firebase.initializeApp(config);

	  var database = firebase.database();
```

### Step 3: Launch app 
Open index.html file via browser (Chrome preferred)

Or visit application via https://lawrencel13110123.github.io/Train-Schedule/

<a name="display"></a>
## App Display

### Demo

![Demo](/assets/demo.gif)
