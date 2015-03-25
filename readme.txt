Zen Cart Lazy Load v1.0
Version Release Date: 7/23/2014
Publisher: PRO-Webs, Inc
Released for Zen Cart v 1.5.3, but should work with all versions if manually 
installed by file merging.

This installation is considered a beginner level Zen Cart module installation.

Lazy Load delays loading of images in long web pages. Images outside of viewport 
are not loaded until user scrolls to them. This is opposite of image preloading. 
Using Lazy Load on long web pages will make the page load faster.

This implementation is a VERY simple usage of Lazy Load intended to use Lazy Load
to load Zen Cart product images more effeciently. The basis is easily adapted to 
other images by tagging the image like below...

<img src="blank.gif" class="lazy" width="240" height="152" />

Note the class "lazy".

This is fairly browser friendly and should work with most, if not all.


INSTALLATION INSTRUCTIONS
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. FIRST MAKE A FULL BACKUP OF YOUR WEBSITE'S FILES AND DATABASE!


2. Merge the file  includes\functions\html_output.php.

You will find 2 changes noted with the following text.

//EDITED FOR LAZY LOAD


3. Upload the javascript file to your custom template directory in to the
   jscript folder.


4. Done.
      

INFORMATION
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Core file Edits: None
Template Override Changes Yes: addition of jscript_lazy.js
Database Changes: None


UNINSTALL
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Remove the package files and file edits in overrides. Removal of the database 
entry is not required to remove this module from use.


SUPPORT
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Please use the PRO-Webs helpdesk https://pro-webs-support.com/


LICENSING
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
lazyload.js (c) Lorenzo Giuliani
Simple Zen Cart integration (c) 2014 PRO-Webs, Inc.


VERSION HISTORY
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1.0 Lazy Load initial release 07/23/2014