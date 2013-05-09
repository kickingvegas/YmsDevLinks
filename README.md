# YMS Dev Links

Building 
Add a links page to your *Xcode Organizer*. Edit the links page using Markdown syntax.



# Requirements
* Xcode 4.6.x
* appledoc

# Installation
1. Install [appledoc](http://gentlebytes.com/appledoc/)
1. Edit `Makefile` to set the variables `PROJECT_NAME`, `COMPANY`, and `COMPANY_ID` to your preference.
1. Edit `docs/index.md` using Markdown syntax to your preference.
1. Run `make` in the project directory to install the links docset into *Xcode Organizer*.

         $ make

# Removal
To delete the docset, open `Xcode preferences > Downloads > Documentation` to find and delete the installed docset.

# Notes
* To traverse back a web page in *Organizer*, you must use a right-mouse button click; not the back button in the bread crumb trail.
