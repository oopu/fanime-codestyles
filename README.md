# fanime-codestyles
Some style conventions for consistent contribution.

What's here?
-----------
This repository contains IDE configurations and overall convention guidelines for languages in use in fanime-* projects.

If you have linting configurations which you'd like to contribute, they should be added here.

How do I use your IDE config files?
------------------

### PHPStorm
*These instructions are written for PHPStorm version 2016.3.*
* Go to File > Settings
* Go to Editor > Code Style
* Click the **Manage** button next to *Schemes* at the top
* Click **Import** and choose the `fanime-conventions-phpstorm.xml` file in this repository under `ide-config/`

I'd also suggest installing the Symfony plugin as well as the PHP Annotations plugin to ease working with fanime-www.

What languages are covered?
----------------------
* PHP *which is largely based on the PHP FIG proposed standards and PSR-2.*
* HTML
* CSS and Scss *very loosely; overall I ask that you follow [BEM](http://getbem.com/introduction/)*
* JS
* Twig
* JSON

**Overall**, use two spaces instead of tabs (just customize your IDE), and when writing HTML or Twig files be mindful of
your page structure. If it only is structured correctly when CSS and JS are loaded, you're doing it wrong for search 
engines and anyone using screen readers for accessibility reasons. 

For more on website accessibility, [check out what Google is contributing to the W3C](https://www.w3.org/TR/WCAG20/) and
check out the [Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)
in Chrome.

Contributing
------------
Anyone is free to create an issue or a pull request! 

If creating a pull request, please reference an issue on the repo and merge-squash your changes into master after they 
have been approved with a commit message like the following:
 
 ``````
   Adds a registration FAQ page
   
   Issue: 9
   PR: 2
   Reviewer: oopu
   
   Other optional notes go here# fanime-codestyles
   