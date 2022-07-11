![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


![light Mode Iphone ](assets/images/iphonexr_landingpage.jpg"light mode landing page")



+ [User Experience](#userexperience "User Experience")
  + [User Stories](#user-stories "User Stories")
  + [User Goals](#user-goals "User Goals")
  + [Requirements](#requirements "Requirements")
  + [Design](#design "Design")
    + [Typography](#typography "Typography")
    + [Personal Bio](#personalbio "Personal Bio")
    + [Contact Page](#contactpage "Contact Page")
    + [Common Features](#commonfeatures "Common Features")
+ [Accessibility](#accessability "Accessability")
  + [Testing](#testing "Testing")
    + [Functionality](#functionality "Functionality")
    + [Styling](#styling "Styling")
    + [Error Log](#errorlog "Error Log")
    + [CSS Validation](#cssvalidation "CSS Validation")
    + [HTML Validation](#htmlvalidation "HTML Validation")

  + [Citations](#citations "Citations")
+ [Lessons Learned](#lessons-learned “Lessons Learned")
+ [Quirks](#quirks "Quirks")
  + [Future Features](#future-features "Future Features")





## Reminders

* Your code must be placed in the `run.py` file
* Your dependencies must be placed in the `requirements.txt` file
* Do not edit any of the other files or your code may not deploy properly

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

-----
Happy coding!
