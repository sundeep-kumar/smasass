# SMASASS (Scalable and Modular Architecture for Syntactically Awesome Style Sheets)

SMASASS (pronounced as smaash!) is a flexible, modular and scalable project; boiler plate based on ideology of SMACSS by Jonathan Snook.

It defines succinct separation of concoction items like:
1. Layout
2. Components
3. Theme
4. Base
5. State
6. Psuedo
7. Typography
8. Vendor lib
9. Media Queries

As state of an element can be represented in three categories:
1. Class Name
2. Psuedo Class
3. Media Query

Those three separations are clearly expressed in every Layout and Module.

#Quick Run

1. Install sass if not done:
http://sass-lang.com/install

2. Clone project by:
git clone https://github.com/sundeep-kumar/smasass.git

3. Build project by:
In terminal run below commands-
"sass main.scss main.css" for scss to css conversion, and
"sass --watch main.scss:main.css" to notice change in .scss file and update your .css

#Depth of Applicability

Since SASS3, being the superset of CSS3; the depth of applicability of syntax changed dramatically for the <SASS3 followers. The industry standard depth of selectors and applicability is being followed with the succinct separation of concoction items, i.e. easy to maintain in long run, scale to any extent and room any unveiled cases (like mixins etc.) to be included in future.

#Isolating Dependencies

Generated css file from compiled main.scss can isolate dependency of project, by separating vendor files and generated css in separate directory. 