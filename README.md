marketo-forms-style
===================

I was asked to share my CSS that makes Marketo's Form 2.0 'plain' stylesheet a little more manageable.

Included, you will find an SCSS file. I use this file with Grunt.js, but anything with an autoprefixer and compass can process it.

I'm still chipping away at this thing, so it is far from perfect. It also has its own opinions, sadly. When I have to override in-line style tags (Marketo, yay!) with !important tags, I've been unsuccessful in resetting some of them. In those cases, I've used the styles I prefered for the projects I use this for.

At the very least, I hope it helps you find all the selectors you need to override Marketo's super-opinionated form 2.0 templates.
