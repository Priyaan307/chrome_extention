# chrome_extention
Milestone-5: Chrome Extension: 21st century bookmarker
Learning Competencies
By the end of this milestone ensure that you

How the browser works?
How to build an extension
Asynchronous javascript
Understand what synchronous and asynchronous code in Javascript means
Understand the Event loop in JavaScript and how code is executed in JavaScript
Iterators and Generators
OddsEnds: Functional Programming
Problem Statement
When Chrome was first released, users praised its speed, but many said they couldn’t switch from Firefox because of the add-ons. Google fixed that in 2009, and the numbers show Chrome gaining users at a much more rapid pace than Firefox is now.
Can you guess how many extensions are there in Chrome and add-ons in firefox now?

What is Chrome extension ?
According to Chrome, it is a small software program that customizes the browsing experience. They enable users to tailor Chrome functionality and behavior to individual needs or preferences. They are built on web technologies such as HTML, JavaScript, and CSS. Learn more here.

Ever wondered How to create a chrome extension ? Well, this week you are going to build a chrome extension that has the following features

Notes and Annotations
Instead of making notes in external applications, attach notes to websites, and pieces of text in them. All without leaving the browser.
Power-Search your History
Instead of bookmarking things, instantly find websites you’ve seen with anything you remember. Search for every word in the text and filter by time, domain, custom tags, bookmarks. Soon also if you shared/liked or cited it on social media.
Cite with precision
Instead of copy-pasting a quote from the article and the url, highlight any piece of text and create a link you can share with anybody. Anyone opening the link will be brought straight to the text you are referring to.
Flexibly Organise
Tag, bookmark and organise websites into lists.
User Privacy
Approach allows us to leave user in full control of their data. By default, all is stored on your computer
Guide
Watch this quick start guide

You can implement any API into your chrome extension. Examples include:

Word Quiz API → Displays a short word association quiz
Daily Quotes API → gives you a random quote every day
Yahoo FInance API → Displays the data of the stocks of your choice when you open a new tab
Football Score API → Displays the score of your football team when you open a new tab.
Releases
Start with setting up your extension. Create a manifest.json file and add the following details to it

add the name of your extension
a short description
version number
add newtab.html to override chrome's new tab, since our extension will open up every time someone opens up a new tab.
in the background property look for scripts. Here goes the JS file that will run in the background.

Explore this list of chrome extension permissions and add the permissions that you need according to the extentsion you choose to build in the permissions property.

add the skeleton of your website to your popup.html file. This may include any image wrappers, buttons, inputs etc.

Create an accompanying popup.js file that contains all the javascript logic for your extension popup.

Now, load your extension into chrome and test it in chrome://extensions.

go to chrome://extensions
Click on Load Unpackaged and select the folder of your extension.
switch developer mode ON
Keep refreshing whenever you make a change to look at the results.
Create an accompanying style.css file → so that your extension doesn't look bland.

Sign in to the API service of your choice and get your API key (you may need to wait a couple of minutes). It's used to identify your project, so don't share it with anyone else.

Making the API call

Now use fetch to call your API by using your API Key. Don't forget to use .catch for handling error cases.

use fetch to call the API and send that data as a response to the frontend.

add a .catch condition to handle any errors you may get.

Follow these instructions to publish your chrome extension to the chrome extensions marketplace
