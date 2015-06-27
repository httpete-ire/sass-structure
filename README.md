#Sass folder structure
example sass folder structure for projects which is based on [SMACSS](https://smacss.com/) by Jonathan Snook. One of the main advantages of following not just the structure but any structure is that people know exactly where the code they want to change is, no longer do you have to filter through a 5000 line css file. One of my pet peeves (and I have been quilty of doing this in the past) is developers overwriting css by tacking it onto the end of the file. Not only does it add to the size of the file but it can also be hard to track down issues.


##Base

The base folder contains boiler plate styles for the project, this includes reset / normalize, typography, forms etc


This folder could be shared between projects as the styles are not specific. 

* _reset.scss
* _typography.scss
* _forms.scss

##Layout

The layout folder contains the grid system for the project and also includes any speific main layout sections (header, footer, container, etc)

* _grids.scss
* _header.scss
* _footer.scss

##Component

The components folder will be the most used throughout the project as it contains the small components that make up the project (media, lists, etc)

* _media.scss
* _profile-cards.scss


##Helper

The helper (also known as util) folder contains Sass speific tools and helpers that can be used throughout the project. It also contains the variables file

* _variables.scss
* _mixins.scss


##Theme

If the project is large and has various themes, they are located here. This folder is optional depending on the project

* _admin.scss
* _user.scss