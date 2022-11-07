# Resumee
The Resumee app is an Android application that shows the resume of a developer.
It is a single scrollable page that can also adapt to landscape mode.
The approach to the design is a minimalistic design to keep it modern and give the user a proper view of the essential information on the developer's resume.

This app is a submission to the HNG I9 Internship stage 2 Task.

### Code Architecture
The logic part of the app is yet to be worked on. But you have the layout written in android XML.
The app includes the use of ScrollView to enable scrolling, ConstraintLayout, LinearLayout for proper positioning of the views and some drawables to create the minimalistic design.

## Design
The design basically consists of a round rectangle set as the background for the profile, two Sans-serif font (Space-Grotesk and Inter) and social media icons.
Yes, I designed the UI components in Photoshop.

## Features 
Some of the features I will still work on includes;
* making it adaptive to different screen sizes.
* making the links interactive.

**Appetize.io link** -https://appetize.io/app/6eqpblr7qyt64fdu4pfaqbbbgq 

## Challenges Encountered
- I made a mistake while naming the file for the signed apk -I was using _keystores\resumee__ with the backslash as file name instead of using only _resumee_.
- The github termninal on my PC was displaying an error  _! [rejected] main -> main (fetch first)_ which took me a long while to resolve with the help of the following commands; 
  1. git pull --rebase origin main
  2. git push -u origin main

### ScreenShots
<img width="175" alt="Potrait" src="https://user-images.githubusercontent.com/99341351/200228922-b5ebd02a-0b58-448e-808c-4d05d14a7a57.png">
<img width="283" alt="Landscape" src="https://user-images.githubusercontent.com/99341351/200228929-fc60c613-7f32-4e48-8710-cdc11bc3dcfd.png">
