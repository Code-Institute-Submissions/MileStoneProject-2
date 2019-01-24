# MileStone Project

## Table of Contents

1. [Brief](#Brief)
1. [UX](#UX)
    1. [Sections](#Sections)
        1. [About us](#About-us)
        1. [Events](#Events)
        1. [Media Catalog](#Media-Catalog)
        1. [Fan Feedback](#Fan-Feedback)
    1. [Wireframes](#Wireframes)
1. [Features](#Features)
    1. [Feature 1 - Sign up Box](#Feature-1-Sign-up-box)
    1. [Feature 2 - Get in touch box](#Feature-2-Get-in-touch-box)
    1. [Feature 3 - Events Box] (#Feature-3-Events-Box)
    1. [Features Left to Implement](#Features-left-to-Implement)
        1. [Forum Board](#Forum-Board)
        1. [Social Links](#Social-Links)
1. [Technologies Used](#Technologies-Used)
1. [Testing](#Testing)
    1. [Small Device layout change](#Small-Device-layout-Change)
    1. [Join us box](#Join-us-box)
    1. [Sign up box](#Sign-up-box)
1. [Deployment](#Deployment)
1. [Content](#Content)

## Brief

CREATE A WEBSITE FOR A BAND
Build a static (front-end only) website for a band. As a starting point, you may want to use wireframes, as we did in the UX lesson (you can use Balsamiq or any other tool, including just pen and paper).

You can use either your assets or the assets within the following GitHub repo.

The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.
You have been given the following requirements after interviews with the client’s representatives:
Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

The band has provided you, the developer, with the following assets that they would like to showcase on their website:

Photos of the band members
A video clip
Audio clips

Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube pages.

## UX

This is the User Interface, the wireframe is in a PDF file that can be found /assets/plans/Bandwireframe.pdf

### Sections

The chosen image that has been used is one of the band pictures given to me.  
It has been chosen the one with all four of them on, their jacket colours have been used to colour the four different pages.  
It has been designed so the navigation bar matches the jacket colours as they appear on the picture when viewed on a small device.

On a small device the Title text would come before the picture, but if viewed on a bigger device the picture would come before the Title text.  
This was an after thought because originally forgot to start with a Mobile first design in mind.  
Then realised afterwards and thats where the adjustment came in.

#### About us

The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.

The information was grabbed from Wikipedia, line breaks where added in afterwards after feedback from my mentor that its not good for a UX if theres blocks of words for people to read.  
2 types of Lines were used:
    The first that is thicker and takes up 100% of the window width.  
    The second takes up a smaller percentage and is a bit thinner.

This design has been followed for the following pages.

Icons were used as well however complications to get them to line up properly fell beyond the time frame allotted so in the end they were removed.  
In the future they would be added.

#### Events

Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

#### Media Catalog

Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

The Media has been separated them into different file formats:
Audio;
Video;
Images;

With the different players in the browser, The players width had to be changed.  This was because on a smaller device the players would exceed the width of the screen.  
Making the UX poor because it would not stay with in the boundary of the device.  Had some issues with trying to set the width in CSS so I had to directly input the width in the HTML code.

CSS was used to create the Image Gallery.

#### Fan Feedback

Fans can post comments about their favourite Monkees Song.

A sign up box was created using Java Script so that people have the ability to eventually sign in and post messages on a forum style board.

### Wireframes

Located in the This is the User Interface, I have created a wireframe in a PDF file that can be found /assets/plans/Bandwireframe.pdf

This shows my basic idea of how i wanted my pages to look like.  I created the wireframe in powerpoint and exported it as an pdf file.

## Features

There are four pages,
About us - This gives a bit of history to the band.
Events - This gives the user the chance to buy tickets for upcoming events.
Media Catalog - This gives the user the ability to listen / download audio files and watch the video in a browser window.  I have also put the images in a CSS Gallery.
Fan Feedback - This is going to be an area where people can leave comments etc.

### Feature 1 - Sign up box

A sign up box was created using Java Script so that people have the ability to eventually sign in and post messages on a forum style board.

### Feature 2 - Get in touch box

A get in touch box was created using Java Script so that people have the ability to get in touch with the band so that they can respond to the user.

### Feature 3 - Events Box

This allows the user to begin the process of purchasing tickets for events.

### Features Left to Implement

Payment screen for the Events Box Form (see above)

#### Forum Board

In the future a forum board could be setup so that people have to login into instead of making a post all board, this stops anonymous abuse of the board.

#### Social Links

The Social links in the footers are not connected to their respective links, however it is ready to implement in the future.
These social links include Facebook, Twitter and YouTube.

## Technologies Used

These are the technologies used in the project:

    Using the Old Bootstrap Version
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" type="text/css" />
    This is to enable the use of Bootstrap with the boundaries of the lessons provided before.

    Using the Font Awesome so I can put icons in https://fontawesome.com/ <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
    This is to enable the use of Font Awesome with the boundaries of the lessons provided before.  There is an experiment to use the new version as well.

    Using the Hover SFX - http://ianlunn.github.io/Hover/  
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css" type="text/css" />
    This is to enable the use of the Hover Styles for the Navigation Bar with the boundaries of the lessons provided before.

    Using my custom style sheet
    <link rel="stylesheet" href="assets/css/style.css" type="text/css" />
    This is to enable the use of my own style of CSS with the boundaries of the lessons provided before.

    Using jquery for Modal Box
    <script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
    This is to enable the use of The Modal Boxes with the boundaries of the lessons provided before.

## Testing

### Small Device layout change

On a smaller device, It looked horrible from a design point to have the image before the title text.  It took a while and help from the Slack Community to get it to the finished product.

    1. open index.html in browser window:
    2. drag window so that the size of the browser changes width to see the change

### Join us box

    1. Go to Events page
    2. Scroll to the bottom of the page
    3. Click on the "Join us" button

### Sign up box

    1. Go to Fanfeedback page
    2. Scroll to the bottom of the page
    3. Click on the "Sign up!" button

## Deployment

Originally I just used it in Cloud9 <https://aws.amazon.com/cloud9/?origin=c9io>, however I was told I could host it through Gitpages <https://github.com/>.

I have also built a Raspiberry Pi that could be a Local Web Server, the only thing I was waiting for my ISP to give me a Static IP Address. <https://www.makeuseof.com/tag/host-website-raspberry-pi/>

Then while I was talking to my Mentor, he told me about Visual Studio Code <https://code.visualstudio.com/>.  
That is what im currently using to finish this project.

I have also downloaded various Apps on my Android Phone to do my coding on the go.

anWriter - <https://play.google.com/store/apps/details?id=com.ansm.anwriter>
This is an editor for HTML, CSS and Java.

Learning Bootstrap - <https://play.google.com/store/apps/details?id=shubham.learningbootstrap>
Offline information about Bootstrap

Openhub for Github - <https://play.google.com/store/apps/details?id=com.thirtydegreesray.openhub>
Allows access to Github

Forker - <https://play.google.com/store/apps/details?id=ch.phcoder.jigit>
Allows access to Github, and also to allow committing file changes.

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

The information that has been used for this project was found on Wikipedia. <https://en.wikipedia.org/wiki/The_Monkees>
The Event Time Table information was got from <https://www.songkick.com/artists/485568-monkees/calendar>
For Reference Information <https://www.w3schools.com/>
For Bootstrap References <https://getbootstrap.com/docs/3.3/>

### Media for Project

I was provided images, audio files and video files from the code institute for this task.

### Acknowledgements

Thank you to my Mentor - Ricardo Quichocho Gallegos (Tech Mentor at Code Institute).