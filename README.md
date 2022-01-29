# WebslingerFA.github.io
HogarthWW Dev Test - Brief
Overview
This document outlines an assignment designed to allow front-end developers to demonstrate their experience and expertise. As well as challenging craft skills, the assignment also presents an opportunity to show capability in the management of timing and technical debt, as well as code maintainability.

Test files
All the required assets are downloadable from here:

dev test (.zip)
Assignment
You’re tasked to modify the provided web project (HTML and CSS), based on the below exercises;

Few things to consider:

You’re not allowed to modify the original CSS (css/style.css). Instead create a new CSS file that contains your overrides,
You’re free to modify the HTML,
You’re not allowed to use Javascript to solve any task.
Running
The project uses absolute links, the HTML won’t load the assets without a “server”. For example:

With Node.js, use https://github.com/zeit/serve
With Python, use https://docs.python.org/2/library/simplehttpserver.html
Exercises
Exercise 1
Add a new hero section.

The current website contains one hero section that shows an image of the moon. You’re tasked to add a new section for space exploration. The new section needs to fit next to the current one instead of on top of it. On mobile, the sections should stack on top of each other.

Current

Current

Expected

Expected on Large

Expected on Small

Assets
Copy: Space. The final frontier.

Background: Use the provided images in assets/images

Extra points
Add a link on the new section that goes to http://space.com/
Fix the alignment of the background image to be always centered
Exercise 2
Fix the order of the timeline.

The current timeline has the correct order in the HTML but it shows differently on the screen. You need to modify the HTML and CSS to make sure the order is correct (by ascending date) on all screen sizes.

Current

Current

Expected

Expected

On Large viewports

1 2
3 4
5 6

On Small viewports

1
2
3
4
5
6
Extra points
Cards style should stay exactly the same
Exercise 3
Support the gallery on older browsers.

The current gallery uses the new CSS grid to position the items. Since we want to support older browsers, you’re tasked to override the grid code and use floats, flex, or similar solutions. Make sure that the gallery will keep same structure and behavior on all viewports.

Current

Current

Extra points
Check for CSS grid support and only use the override code where it's not supported
Delivery
Deliver back the project folder with your modified HTML and CSS in a zipped folder to: elie_eid@apple.com
