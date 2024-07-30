# VanZTechBlog

The world of technology thrives not only on innovation but also on the sharing of knowledge. This exchange of ideas is vital, as it fosters a community where concepts are clarified, advancements are discussed, and new technologies are explored. Every search for a technical topic reveals a wealth of articles, tutorials, and discussions authored by developers from all corners of the globe, demonstrating the value of writing as a means to both teach and learn in the ever-evolving tech landscape. This CMS-style blog site, developers can publish their blog posts so they are available to the public.  This app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## User Story

AS A developer who writes about tech<br>
I WANT a CMS-style blog site<br>
SO THAT I can publish articles, blog posts, and my thoughts and opinions

## Acceptance Criteria

GIVEN a CMS-style blog site
* WHEN I visit the site for the first time<br>
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
* WHEN I click on the homepage option<br>
THEN I am taken to the homepage
* WHEN I click on any other links in the navigation<br>
THEN I am prompted to either sign up or sign in
* WHEN I choose to sign up<br>
THEN I am prompted to create a username and password
* WHEN I click on the sign-up button<br>
THEN my user credentials are saved and I am logged into the site
* WHEN I revisit the site at a later time and choose to sign in<br>
THEN I am prompted to enter my username and password
* WHEN I am signed in to the site<br>
THEN I see navigation links for the homepage, the dashboard, and the option to log out
* WHEN I click on the homepage option in the navigation<br>
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
* WHEN I click on an existing blog post<br>
THEN I am presented with the post title, contents, post creator’s username, and date created for that post
* WHEN I click on the dashboard option in the navigation<br>
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
* WHEN I click on the button to add a new blog post<br>
THEN I am prompted to enter both a title and contents for my blog post
* WHEN I click on the button to create a new blog post<br>
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
* WHEN I click on one of my existing posts in the dashboard<br>
THEN I am able to delete or update my post and taken back to an updated dashboard
* WHEN I click on the logout option in the navigation<br>
THEN I am signed out of the site
* WHEN I am idle on the site for more than a set time<br>
THEN I am able to view posts and comments but I am prompted to log in again before I can add or delete posts

## Go to my project
  
You can take a look at my blog [here](https://vanztechblog.onrender.com/)

## Visual reference of project
The following image demonstrates the app's appearance:
  
![gif reference](./assets/image-reference.gif)

## License
![GitHub](https://img.shields.io/github/license/VanZittle/VanZTechBlog?style=for-the-badge)<br> Go to license [here](https://github.com/VanZittle/VanZTechBlog/blob/main/LICENSE)
  
Markdown generated with **[README Creator](https://github.com/VanZittle/module9-challenge-ReadmeGenerator)**
