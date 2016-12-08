# Hebrew-Keyboard---Polytonic
Alternate Israeli Hebrew keyboards layout for OS X with quick access to nikud

=======
File made with [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) the Mac OS X Keyboard Layout Editor. 


This Hebrew keyboard is a layout that lends itself to writing for Ancient Near Eastern Studies, namely there are Unicode character mappings for commonly used for nikud and other common character.  


## How to use the code
1. Paste the code into a text editor, e.g. [Atom](atom.io), TextEdit, TextWrangler, SublimeText
  * To rename the keyboard name, rename the value `name` in the line `<keyboard group="126" id="-2" name="Hebrew Polytonic 1.2" maxout="3">`. This is the name that shows up in the keyboard menu after installation. 
2. Save with the file extension `.keylayout`, e.g. `HebrewPolytonic.keylayout` in /Library/Keyboard layouts/ (could also be on User ~/Library/Keyboard layouts, but this is where I keep mine). You might need to make a directory if one doesn't exist. 
3. Now go to System Preferences > Keyboard and depending on your system (e.g. 10.*), there will be a way to add a new keyboard.
  * In 10.6, the full list of all keyboards were available and after enabling your new keyboard, you had to make sure an app you want to use the keyboard in launches anew in order for the app to *see* the new keyboard. Since I wanted to use the layout in more than one app, I'd usually just log out and in. In 10.9, this is no longer required :thumbsup:
4. If you want to have an icon for your keyboard, you'll need to add an `.icns` with the exact `name` as you gave it in 
 `<keyboard group="126" id="-2" name="ANE v3.5" maxout="3">` above

## How to see the characters available? 
### Option and Option Shift
#### Direct input


1. Turn on **Show Keyboard Viewer** 
2. Now press `Shift` and notice the characters that have changed, e.g. 
3. Do the same now with 'Option' and even more with 'Option-Shift' you'll see not only some characters. 



### Known Issues
