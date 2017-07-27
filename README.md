# Responsive-Portfolio

Overview

In this assignment, you'll create two different portfolios. The first will be an update of the one you made last week—you'll enhance this one with a mobile-responsive layout. For your second portfolio, you’ll build a layout with the Bootstrap CSS framework.

Remember

You will be fully capable of doing this homework by the end of Saturday's class.

Before You Begin

You've learned a ton of material these past two weeks: html/CSS, GitHub, Heroku and Bootstrap. If you feel like you're falling behind, there's no need to panic. You'll have 22 weeks to digest and master this material.

We're diving into JavaScript next week, and html/CSS will start getting less focus. Still, you'll find that a basic knowledge of html/CSS will help you understand JavaScript, especially when we use it to manipulate web pages.

Instructions

Create two new GitHub repositories and name them Responsive-Portfolio and Bootstrap-Portfolio.

Clone these repositories to your computer.

Copy the contents of Basic-Portfolio (your first homework solution) and paste the mentioned files into Responsive-Portfolio.

Note: Be sure not to include any dot files (e.g .git, .gitignore for example) from the Basic-Portfolio repo.
If you chose the Skeleton exercise for your first homework assignment, contact a TA, who will provide you with a template for your portfolio.
Assignment One Instructions - (No Bootstrap)

Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.
Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.
You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.
768px is about the width of a tablet and 640px is about the width of a phone in landscape.
Make the layout match the following screenshots:
index.html: 980px, 768px, 640px
portfolio.html: 980px, 768px, 640px
contact.html: 980px, 768px, 640px
Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices.

Protip: Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.

Assignment Two Instructions (Bootstrap)

Inside your Bootstrap-Portfolio repo, create index.html, portfolio.html and contact.html.

Use Bootstrap CSS to recreate the portfolio you built last week. Your Bootstrap solution should not make explicit use of media queries.

Find a Bootstrap theme that you like (or make your own - it isn't too tough if you follow the bootstrap documentation!). There are plenty of free options available, or you can pay for one if you choose. Here are a few site where you can find themes.

Wrap Bootstrap
Boots Watch
Start Bootstrap
Theme Forest
Bootstrap Skins
Blacktie
Install the bootstrap theme and add your portfolio content

Be sure to leave space for your future projects that you will be coding during the course
This is your opportunity to shine! Add your own images, correct contact information and link to homework one as part of your portfolio (if you liked it :).
Create the index.php and composer.json inside Bootstrap-Portfolio

Make sure you have <?php include_once("yourFileNameHere"); ?> and {} for those files.
Deploy your new Bootstrap-powered portfolio to Heroku. Remember:
heroku login
heroku create
git push heroku master
Alternatively, deploy your new portfolio using the gh_pages branch of your repository.
Submitting Your Work on BootcampSpot.com

Submit the GitHub links to your portfolio repositories on GitHub.

If you deployed to Heroku, submit the link to your Heroku site in the same input field.

BONUS

Incorporate CSS animations in your portfolio. More info here.
One More Thing

If you have any questions about this project or about the material we covered, the instructor and your TAs are only a Slack message away.

Good Luck!

Copyright

Coding Boot Camp (C) 2016. All Rights Reserved.
