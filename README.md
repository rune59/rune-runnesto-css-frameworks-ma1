# Module Assignment

## Goal

To practice creating page layouts using Bootstrap and Sass.

## Brief
Using Bootstrap and Sass, code the supplied design into a responsive layout.

## Level 1 Process
You can use the CDN version of Bootstrap or customise the library using the source Bootstrap Sass files.

## Level 2 Process
Use BEM to name your custom classes. Add them to the elements in addition to Bootstrap’s classes since Bootstrap does not follow BEM.

## Resources
The required files can be found here: https://lms.noroff.no/mod/folder/view.php?id=41249



## Submission
- Create a repository in your GitHub account called your-name-css-frameworks-ma1, e.g. mary-smith-css-frameworks-ma1 and make sure it's public.

-  Add, commit and push all your code to this repo.

- Submit the repo link.


## Notes
-  The files in the folder "bootstrap-scss" contains all the program files in the bootstrap framework. 

- These files must be imported to the file "sass/style.scss" to be interpreted as css-files and compiled to css-files. 

- The settings is made to only compile files in the file style.scss til css. 

- When the bootstrap files has been downloaded to the folder "bootstrap-scss" and from there imported to the file "style.scss", the link to the bootstrap in the head section of the html-files can be deleted.

- CSS-variables need to be changed to SCSS-variables, with a $ prefix. In the _custom.scss file. 

- The CSS-files in the folder "css" has been copied to the partials folder.
Except the file _variables.css, which has been copied to the file _custom.scss. This includes the files _home.css, _layout.css, _nav.css and _typography.css. Then the extension of these files has been changed to .scss. 


## Thinks that do not work
- The color indicating which nav element is active, is not 
working.
- I removed the link to cdn (bootstrap) in the index.html, but unfortunately that had the consequence that the styling of the navbar changed in an unpredicted way. And the cards were no longer restricted to showing maximum 4 cards in a row. Why is this?
- The @media for the class footer-styling does not work. 

