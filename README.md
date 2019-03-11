<h1>Pick A Dish</h1>
<br>
First Project: <i>User-Centric Frontend Development</i>

My project is a static frontpage website aimed at people who have the ingredients available but have no idea what to do with them.
So for example if you have some lettuce in the fridge and some chicken in the freezer and you have no idea what to make then you can input salad as a starter then chicken as a main and a random recipe will show that you can use or
define more of the ingredients to make a more narrowed search.
Also it will have recipes of the day that will alternate daily.

<h2>UX</h2>
<br>
This website is mainly focused on users who are wanting a variety of meals with little thinking about what meal specifically. This allows for a more varied and open palette with different foods and flavours then they would have if they 
went through a book or other site as they are generally structured in a way that makes the user need a meal idea in mind.
I think this site would be very used as users now want to have variety and speed with little thinking on there end.

<ul>
<li><b>User 1:</b> I want a quick meal using some chicken and a pepper I have in my fridge, I input chicken in the main and have a recipe appear that uses these ingredients with little thought on my part.</li>
<li><b>User 2:</b> I am having guests around and would like a starter, main and dessert but dont know what will go well together, I input salad in starter as that is one ingredient I am using and select option "similar" for mains and dessert, 
then I am offered a main dish of fish for example and a dessert like macarons which if I havent got the ingredients for I can use as a basis for selecting a new recipe.</li>
<li><b>User 3:</b> I have a dish I do alot but would like a different take on it so I input the specific ingredient and click on option "similar" which shows me my dish but using a different main ingredient.</li>
</ul>

<h4>Wireframes/Designs</h4>
They can be found in the folder /wireframes.

<h2>Features</h2>
<br>
The first part the user sees is a nice clean, minimal design with an enticing picture of a dish with a minimal designed Logo and name.
The second part the user sees is the navigation bar which is again designed to be minimal with enough information to let the user know what it does.
The next part would be a brief description of the site and what it does followed by a selection of "dishes of the day" which give an quick idea incase of time constraints of the user.
The next part would likely be the Starter, Main and/or Dessert sections which is designed to focus on the selection box with a very little to distract the user.
The final part would be the footer which houses the T&C, an about/bio section with mentions if needed and social media links.

I would like to host a live/recorded cook-along with different people able to upload or livestream themselfs cooking to allow people to go along at home with it.
I would also like a kids cooking section that allows people to get there kids to help with the dishes or with other parts of the meals.

<h2>Features Left to Implement</h2>
<br>
Interactive diagram/picture with selectable food items to allow for a more visual approach.

<h2>Technologies</h2>
<br>
<li><b>HTML5</b></li>
<li><b>CSS</b></li>
<li><b>Bootstrap</b> (4.3.1)</li>

<h2>Testing</h2>
<br>

My first test was to input the code on <a href="https://validator.w3.org">https://validator.w3.org<a> and tidy up any mistakes I made, I did thiss 4 times until all was rectified.
Next I did the same for my CSS on <a href="https://jigsaw.w3.org/css-validator/validator">https://jigsaw.w3.org/css-validator/validator<a> and got an all clear on my code.

My next step was to make sure I could complete my UX user tasks as I set them out so I started at user one and could easily find out what I needed to know.
User two was next so I went to the starter section and clicked on salad, then I was taked to a recipe page were I clicked on <b>Show Similar</b> and was taken to a main then from ther to a dessert so that was a success.
User three was trickier as I had to modify my site to allow completion of the task but could accomplish it.

I tested out the site on various resolutions and mobile devices to make sure it was working well, there were a few problems and overlaps but I resolved these and the site was working well.
The signup / signin forms will state <b>"Please fill in this field"</b> if left blank and will not submit. If all fields are valid it will send the data and reload the page and place the user at the top.

Only the T & C privacy policy will open in a new tab using the <b>target="_blank"</b> as this is not part of the flow of the site.

All the navbar links take you to the corresponding page/ section of page and also the main logo links back to index.html.

The site was tested on multiple browsers and systems such as <ul>
<li>Chrome</li>
<li>Internet Explorer</li>
<li>Firefox</li>
<li>Safari</li>
<li>Iphone 8</li>
<li>Samsung Galaxy S8+</li>
<li>LG G6</li>
</ul>
This was to make sure it worked across multiple devices and systems.
The background image was clipping on mobile and the logo was further down then I wanted so I found out the <b>height="50vh"</b> was not the culprit so removed this in style.css and the problem was fixed.

<h2>Deployment</h2>
<br>
This site is hosted on GitHub Pages, using the master branch to deploy. 
The site will update automatically upon new commits to the master branch. 
In order for the site to deploy correctly, the landing page must be named index.html.

You can clone this repository directly into the editor of your choice by pasting git clone https://github.com/m-harwood/pick-a-dish-first-project.git into your terminal to run locally.
To cut ties with this GitHub repository, type git remote rm origin into the terminal.

<h2>Credits</h2>
<br>
<h4>Content</h4>

All content across this site is written by me.

<h4>Media</h4>

The photos used in this site were obtained from https://pxhere.com and are CC0 Public Domain free to use.
They are resized and compressed to allow faster load times.

<h4>Acknowledgements</h4>

I received inspiration for this project from the many food websites and cooking shows, also sometimes from my own lack of imagination with coming up with meal ideas for a family.