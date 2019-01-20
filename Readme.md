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

## UX

This is the User Interface, I have created a wireframe in a PDF file that can be found /assets/plans/Bandwireframe.pdf

### Sections

I have chosen a one of the band pictures given to me.  I have chosen the one with all four of them on, I thought it would be a good idea to use their jacket colours to colour my four different pages.  I have also designed the navigation bar to match the jacket colours as they appear on the picture when viewed on a small device.

I also have made it so that on a small device the Title text would come before the picture, but if viewed on a bigger device the picture would come before the Title text.  This was an after thought because I forgot to start with a Mobile first design in mind.  Then realised afterwards and thats where the adjustment came in.

#### About us (Home Page)

The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world.

The information was grabbed from Wikipedia, I added in the line breaks in afterwards after feedback from my mentor that its not good for a UX if theres blocks of words for people to read.  So I added in 2 types of Lines, the first that is thicker and takes up 100% of the window width.  The second takes up a smaller percentage and is a bit thinner.

This design has been followed for the following pages.

I used icons as well however I struggled to get them to line up properly so in the end I removed them and came up with the design I have finished with.  In the future I would like to add icons, that is something I would like to work towards learning.

#### Events

Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

As I write this I have forgotten to actually do the above request.  So I will make that fix that now.

Fixed that issue, had a problem with how it views because it was coming up as two different styles.  

#### Media Catalog

Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

I have seperated them into different file formats:
Audio;
Video;
Images;

With the different players in the browser, I had to change the width of the players.  This was because on a smaller device the players would exceed the width of the screen.  Making the UX poor because it would not stay with in the boundary of the device.  Had some issues with trying to set the width in CSS so I had to directly input the width in the HTML code.

I used CSS to create the Image Gallery.

#### Fan Feedback

Fans can post comments about their favourite Monkees Song.

I have created a signup box using Java Script so that people have the ability to eventually sign in and post messages on a forum style board.

### User Goals

#### I want to provide information about

##### The Band

History, Members etc

##### Past Events

Places they have played at in what year and to give the User a chance to get in touch with the Band.

##### Media

Pictures, Music, Videos

##### Fan Feed back

Opportunity for Fans to publish comments, and join them on social media pages

### Wireframes

Located in the This is the User Interface, I have created a wireframe in a PDF file that can be found /assets/plans/Bandwireframe.pdf

This shows my basic idea of how i wanted my pages to look like.  I created the wireframe in powerpoint and exported it as an pdf file.

## Features

I have four pages,
About us - This gives a bit of history to the band.
Events - This gives information about what they have been doing for the past few decades.
Media Catalog - This gives the user the ability to listen / download audio files and watch the video in a browser window.  I have also put the images in a CSS Gallery.
Fan Feedback - This is going to be an area where people can leave comments etc.

### Feature 1 - Sign up box

I have created a signup box using Java Script so that people have the ability to eventually sign in and post messages on a forum style board.

### Feature 2 - Get in touch box

I have created a get in touch box using Java Script so that people have the ability to get in touch with the band so that they can respond to the user.

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

The information I have found for this project regarding the band was found on Wikipedia. <https://en.wikipedia.org/wiki/The_Monkees>

### Media for Project

I was provided images, audio files and video files from the code instute for this task.

### Acknowledgements

Thank you to my Mentor - Ricardo Quichocho Gallegos (Tech Mentor at Code Institute).