# YmsDevLinks
Sometimes, you really don't need to leave **Xcode** to get to the web. **YmsDevLinks** lets you create your own links page in **Xcode Organizer**. Edit your page using Markdown syntax.

From within **Xcode Organizer**, get access to:
* Apple Developer links (forums, bug reporter, videos, iTunes Connect)
* Search Google and Stack Overflow
* Add links to your own projects

![YmsDevLinks in Xcode Organizer](http://kickingvegas.github.io/YmsDevLinks/images/ymsdevlinks.jpg)

**YmsDevLinks** takes advantage of [appledoc](http://gentlebytes.com/appledoc/) to install your links page into **Xcode**.

# Requirements
* Xcode 4.6.x
* appledoc

# Installation
1. Install [appledoc](http://gentlebytes.com/appledoc/)
1. Edit `Makefile` to set the variables `PROJECT_NAME`, `COMPANY`, and `COMPANY_ID` to your preference.
1. Edit `docs/index.md` using Markdown syntax to your preference.
1. Run `make` in the project directory to install the links docset into **Xcode Organizer**.

         $ make

# Protip
In **Organizer** change the docset search so that you only search the API versions you really [need](http://stackoverflow.com/questions/9523399/why-is-xcode-documentation-search-performance-so-terrible). 

# Removal
To delete the docset, open `Xcode Preferences > Downloads > Documentation` to find and delete the installed docset.

# Notes
To traverse back a web page in **Organizer**, use a right-mouse button click - the back button in the **Organizer** bread-crumb trail only works on docset pages.

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





