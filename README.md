# Windows95-HTML
A Windows 95 experience written in HTML5.

This documentation is a work-in-progress and will be updated more later. Be sure to read the known issues section before you test it out. 

####Programs:
The main program that works is the Run dialog (Start -> Run). From there, you can run:

* winver
*debug

I would like to add:

* cmd (to run dostoy, mentioned below)
* notepad
* defrag
* Internet Explorer (basically an iframe with an address bar)

####Known Issues:
* You can only hide the Start Menu by clicking the Start Button in the taskbar. This will be fixed shortly.
* The start menu has no levels below the top level

####Desktop
No work has been done on the actual Desktop yet, but the original developer planned for it to be just like a standard application window that stays at a z-index of 1, running root-level JS execution (index.htm and desktop.js)

Would like to have:

* folders (with say "my music" and "my videos", "my articles" etc)
* Perhaps https://github.com/captbaritone/winamp2-js can be used as a portfolio for musicians?

####MS-DOS Prompt
The original developer was going to use JS-Dosbox, but I don't like that app. I might add it as a one-off, to run a particular old DOS game that I used to love (ATC, anyone?), but for now I've included https://github.com/toolsley/dostoy which can be modified as needed. It could be interesting to have dostoy be the website at the beginning, but users can type "win" at the prompt to load up windows 95. Would need to get the splash screen _just_ right for that though.
