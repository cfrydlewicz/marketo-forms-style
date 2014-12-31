marketo-forms-style
===================

I was asked to share my CSS that makes Marketo's Form 2.0 'plain' stylesheet a little more manageable.

Included, you will find an SCSS file. I use this file with Grunt.js, but anything with an autoprefixer and compass can process it.

I'm still chipping away at this thing, so it is far from perfect. It also has its own opinions, sadly. When I have to override in-line style tags (Marketo, yay!) with !important tags, I've been unsuccessful in resetting some of them. In those cases, I've used the styles I prefered for the projects I use this for.

At the very least, I hope it helps you find all the selectors you need to override Marketo's super-opinionated form 2.0 templates.


To Use It
=========
I wrap a div classed 'embedded-marketo-form' around the Embed script Marketo uses. That allows me to control and override Marketo's styles easily and allows me to distinguish it from our legacy forms that use iframes.

When setting up your Form in the 2.0 editor in Marketo Design Studio, make sure you choose their 'Plain' template. At the time of this writing, it was the last option in the list.

Change the crap out of it. I've probably done lots of annoying stuff and I left my breakpoints in there out of sheer laziness. But at least you can see my work and undo it more easily than you can work on Marketo's sheets.


Shameless Plug
==============
http://corryfrydlewicz.com
