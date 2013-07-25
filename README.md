Flatstrap
=========
Flatstrap is css file for Twitter Bootstrap and make it be flat ui. Simple. Don't need to edit bootstrap css. Use this css with bootstrap together.

Target
========
Remove these css.
- box-shadow
- background color gradient
- round corner (This will write code in flatstrap-no-round-corner.css seperate from flatstrap.css.)

Why you should use this?
=========
I know very well that in the internet. I don't be first person to think about flat ui on bootstrap.
I saw <a href="http://www.littlesparkvt.com/flatstrap/">littlesparkvt.com/flatstrap</a> but you know?
It don't make sense that I should wait littlesparkvt release flat version when bootstrap update later and
when I want to <a href="http://twitter.github.io/bootstrap/customize.html">customize bootstrap</a>.
I can't do it because flatstrap is pre-generated.

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
