# MileStone Project

I have been tasked with building a website for a band,

This is my brief;

CREATE A WEBSITE FOR A BAND
Build a static (front-end only) website for a band. As a starting point, you may want to use wireframes, as we did in the UX lesson (you can use Balsamiq or any other tool, including just pen and paper). You can use either your assets or the assets within the following GitHub repo.
The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. You have been given the following requirements after interviews with the client’s representatives:
Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.
Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.
The band has provided you, the developer, with the following assets that they would like to showcase on their website:
Photos of the band members
A video clip
Audio clips
Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube pages.

Create a website of around 4-5 pages, or (if using a single scrolling page) these should be separate page areas.
Incorporate main navigation and grid layout (you might want to use Flexbox or Bootstrap to accomplish this).
Whenever possible, strive to use semantic HTML5 elements to structure your HTML code better.
Make sure your site is as responsive as possible. You can test this by checking the website on different screen sizes and browsers.
We advise that you write down user stories and create wireframes/mockups before embarking on full-blown development.
The site can also make use of CSS frameworks such as Bootstrap, just make sure you maintain a clear separation between the library code and your code.
You should conduct and document tests to ensure that all of your website’s functionality works well.
Write a README.md file for your project that explains what the project does and the need that it fulfills. It should also describe the functionality of the project, as well as the technologies used. Detail how the project was deployed and tested and if some of the work was based on other code, explain what was kept and how it was changed to fit your need. A project submitted without a README.md file will FAIL.
Use Git & GitHub for version control. Each new piece of functionality should be in a separate commit.
Deploy the final version of your code to a hosting platform such as GitHub Pages.
 
## UX
 
### Sections 

## About us (Home Page)
The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.

## Media Catalog
Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

## Events
Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

## Fan Feedback
Fans can post comments about their favourite Monkees Song

### User Goals

#### I want to provide information about

##### The Band
History, Members etc

##### Events
Places they have played at in what year

##### Media
Pictures, Music, Videos

##### Fan Feedback
Opportunity for Fans to publish comments, and join them on social media pages

### Wireframes

Located in the /assets/plans/

is a pdf file called Bandwireframe.pdf

This shows my basic idea of how i wanted my pages to look like.  I created the wireframe in powerpoint and exported it as an pdf file.


## Features

I have four pages,
About us - This gives a bit of history to the band.
Events - This gives information about what they have been doing for the past few decades.
Media Catalog - This gives the user the ability to listen / download audio files and watch the video in a browser window.  I have also put the images in a CSS Gallery.
Fan Feedback - This is going to be an area where people can leave comments etc.
 
### Feature 1 - Sign up box
I have created a signup box using Java Script so that people have the ability to eventually sign in and post messages on a forum style board.


### Features Left to Implement

#### Forum Board
I would like to setup a forum board that people have to login into instead of making a post all board, this stops anonymous abuse of the board.

#### Social Links
I have left the Social links in the footers ready to implement in the future.
These social links include Facebook, Twitter and YouTube.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

    Using the Old Bootstrap Version <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" type="text/css" />
    Using the Font Awesome so I can put icons in https://fontawesome.com/ <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
    Using the Hover SFX - http://ianlunn.github.io/Hover/  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css" type="text/css" />
    Using my custom style sheet <link rel="stylesheet" href="assets/css/style.css" type="text/css" />
    Using jquery for Modal Box - <script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

Originally I just used it in Cloud9, however I was told I could host it through Gitpages.


In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content

The information I have found for this project regarding the band was found on Wikipedia. https://en.wikipedia.org/wiki/The_Monkees

### Media

I was provided images, audio files and video files from the code instute for this task.

### Acknowledgements

- I received inspiration for this project from X