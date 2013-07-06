Flatstrap
=========
Flatstrap is css file for Twitter Bootstrap and make it be flat ui. Simple. Don't need to edit bootstrap css. Use this css with bootstrap together.

Target
========
Remove these css.
- box-shadow
- background color gradient
- round corner (This will write code in flatstrap-no-round-corner.css seperate from flatstrap.css.)

Howto
========
Place flatstrap.css under bootstrap-responsive.css. It will overwrite css of Bootstrap and make it to flat ui. 

If you don't want round corner or want metro ui,  include flatstrap-no-round-corner.css with flatstrap.css too. It will make anything be square.

Example code
========
```html
<link href="bootstrap/bootstrap.css" rel="stylesheet">
<link href="bootstrap/bootstrap-responsive.css" rel="stylesheet">
<link href="flatstrap.css" rel="stylesheet">
<link href="flatstrap-no-round-corner.css" rel="stylesheet">
```