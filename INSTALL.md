To install this you need two things:

```GitHub```: which I am guessing you already have <br>
```Git```: we will use git as a better way to install and implement this but you do not have to because I will show a way to not use Git and still make the configuration


<hr>

DISCLAIMER:
 - Before anything enable the option `toolkit.legacyUserProfileCustomizations.stylesheets` from your `about:config` if you haven't already

## Installation with Git

First off, open up your terminal. Doesn't matter which shell you're using, just type in:

```git clone https://github.com/Filip-Nachov/Firefox-Theme.git```

That'll fetch the theme from GitHub and get it set up.

Now, fire up Firefox and in the address bar, type in about:profiles and hit Enter. This will pop up a window showing your Firefox profiles. Scroll down until you see "Root directory" and click on "Open Folder" next to it.

This will open up a folder in your file manager. In there, find where you downloaded the GitHub repository. Grab the user.js file from there and drop it into the folder you just opened from the browser.

Still in that folder, make a new folder named chrome. Inside that, put the UserChrome.css file from the GitHub download.

Close Firefox and open it again. 

## Installation without Git

First things first, head over to Firefox-Theme on GitHub. Once you're there, look for the "Code" button and click on it, then select "Download ZIP".

Once the ZIP file is downloaded, unzip it.

Now, open up Firefox and type about:profiles into the address bar and hit Enter. This will open up your Firefox profiles.

Scroll down until you see "Root directory" and click on "Open Folder" next to it. This will open up a folder in your file manager.

In there, find where you unzipped the downloaded ZIP file. Grab the user.js file from there and drop it into the folder you just opened from the browser.
Still in that folder, make a new folder named chrome. Inside that, put the UserChrome.css file from the unzipped folder.
Close Firefox and open it again. Your new theme should now be applied!
