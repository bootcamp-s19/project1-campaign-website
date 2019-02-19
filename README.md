#
# Project 1: Campaign Website


**Description**

Create a website promoting your favorite \*\*FICTIONAL\*\* character from a book, TV show, movie, or graphic novel, who is running for the elected position of Constable in your magistrate district of Fayette County. (There are 3 such districts.)

Briefly research the role of Constable, then design a political website for your chosen character. Here&#39;s a link to get you started: [https://en.wikipedia.org/wiki/Constables\_in\_the\_United\_States#Kentucky](https://en.wikipedia.org/wiki/Constables_in_the_United_States#Kentucky)

**Website Content**

Your website should introduce the public to your candidate, explain why they are running, and list three issues that are important to them.

Your job is to make it easy for voters to see whether your candidate&#39;s beliefs align with their own.

To keep things light and fun, pick issues that pertain to the character in their fictional setting, not the real world. :-)

**Objectives**

To complete the assignment, you must:

1. Setup: Heroku account if not already setup
2. Setup: Establish Express server locally
3. Fork existing repo: [https://github.com/bootcamp-s19/project1](https://github.com/bootcamp-s19/project1)
4. Clone the forked repo locally in your ~/Sites/project1 folder
5. Add a style.css file to the /css directory
6. Edit the index.html file to include the css file
7. Edit the index.html file to include the Bootstrap reference via CDN
8. Development: Add content and elements to your website
9. Development: View changes locally with Express
10. Deployment: Create Heroku App with existing repo
        heroku git:remote -a project1

11. Deployment: Push your code to Github remote
12. Push your code to Heroku remote
13. View your website on your laptop and phone
14. Post links to your Github repo and Heroku application to the Project 1 Slack channel.

**Application file structure**

Minimally:
app/
    index.html - main page
    css/ - folder to contain css files
       /style.css - stylesheet
    img/ - folder to contain any images
app.js - file to run express
composer.json - file for composer
composer.lock - lock file for composer
Procfile - **no** file extension
Readme.txt -
.gitignore -

Additional pages will be relative to the index.html file.

It is okay if your project has more files and more directories, but at the least you need the ones listed above.

**Requirements**

Website must be responsive

- Choose Four Bootstrap Components to include from this list:

| Badge | Button | Caption | Card | Collapse |
| --- | --- | --- | --- | --- |
| Icon | List Group | Media Object | Popovers | Tooltip |

- Augment Five Bootstrap Utilities to suit the needs of your website

Remember to include :

1. A few (more than 3) prominent pictures of your candidate
2. A table displaying important information for voters
3. A call to action - election day is November 5!

Scroll to an anchor tag

Punch out to a website

**Remember to push to Github!**

Your repo should be public so that others can see your code and comment on it.

**Remember to deploy to Heroku!**

You will need to follow our example boilerplate to set up an Express server.

You will also need to include a Procfile so Heroku knows how to start your server.

**If you finish early...**

Continue to add content and pages to your site and improve the styling.

Implement bootstrap components from this list that will enhance your site

| Carousel | Jumbotron | Nav/Navbar |
| --- | --- | --- |
| Progress | Spinner | Jumbotron |

Download Bootstrap and compile via Sass instead of using CDN



**If you get stuck...**

Ask. :-)
## Additional Resouces

For more information about using PHP on Heroku, see these Dev Center articles:

- [Getting Started with PHP on Heroku](https://devcenter.heroku.com/articles/getting-started-with-php)
- [PHP on Heroku](https://devcenter.heroku.com/categories/php)
- [![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
