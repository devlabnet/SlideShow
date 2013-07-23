SlideShow
=========
SlideShow Plugin for CKEditor

A cool plugin which allow to create and manage SlideShow in CKEditor.
You can easily Add, Remove images to create the Slide Show. 

Specification
-------------
The plugin has been designed to work with the "Ad-Gallery" javascript slidshow program available at the 
following location : http://adgallery.codeplex.com, and with "FancyBox" java program available at the 
following location : http://fancybox.net/.
For each slide show created with this plugin, you can adjust most of the available controls 
available in ad-gallery :

    Slide Effect.
    Animation Speed.
    Animation Delay.
    Auto Start
    Show / Hide Thumbnails.
    Sho / Hide "Start - Stop" Buttons
    Open Image on Click (with a FancyBox pop-up).
    ...  

Internationalization
-------------------------
Currently plugin supports 2 languages.

* en
* tr

*Translations are welcomed.*

Usage
-------------------------
1. Download source files and place them on to be created "slideshow" folder under the CKeditor's plugin base.
2. Define plugin in CKEDITOR config object.
        CKEDITOR.config.extraPlugins = 'slideshow';
3. Set your CKEDITOR language if you did not set it yet.
        CKEDITOR.config.language = 'en';
4. Place the "ad-gallery" and "fancybox" directories at the same level of the ckeditor directory.
5. You're Done !! Just enjoy.

The 2 directories "ad-gallery" and "fancybox" have to be placed at the same level as the ckeditor directory.
They are just copy of the files from respective web sites (ad-gallery and fancybox), just a fews modifs have been made
in the as-gallery css file, for info, and for curious people, the diffs compared to the original are in the patch 
file under this ad-gallery directory.
The location of these directiries can be changed by editing "slidesho.js" and updating the variables on top of
this file.
        
Requirements
-------------------------
To correctly work, you need to have access to CKEditor, KCFinder (or any stuff to allow to upkoad images
on the server), ad-gallery javascript / css and fancybox javascript and css.

Demo
-------------------------
[View the live demo](http://www.slideshow.promo-stic.fr/).


Cheers
--------------------
Thanks to [CKeditor] [1] and [ad-gallery] [2] and [fancybox] [3] people for their good work.

  [1]: http://ckeditor.com              "CKeditor"
  [2]: http://adgallery.codeplex.com    "ad-gallery"
  [3]: http://fancybox.net/             "fancybox"
