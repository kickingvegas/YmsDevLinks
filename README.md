# YmsDevLinks

Sometimes, you really don't need to leave Xcode to get to the web. **YmsDevLinks** lets you create a links page to put in **Xcode Organizer**. Edit your links page using Markdown syntax.

Get access from within **Xcode Organizer** to:
* Apple Developer links (forums, bug reporter, videos, iTunes Connect)
* Search Google and Stack Overflow.
* Add links your own projects

![YmsDevLinks in Xcode Organizer](http://kickingvegas.github.io/YmsDevLinks/images/ymsdevlinks.jpg)

**YmsDevLinks** takes advantage of [appledoc](http://gentlebytes.com/appledoc/) to build and install your links page into Xcode.

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

# License

    Copyright 2013 Yummy Melon Software LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

    Author: Charles Y. Choi <charles.choi@yummymelon.com>





