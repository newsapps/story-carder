story-carder
============

A simple web app that lets you enter in your story cards, a la the Menlo Innovations way, and print them for your storyboard.

This code relies on Tabletop.js, a project by Balance Media and WNYC: http://builtbybalance.com/Tabletop/

You need a few things to start:
* A printer that can print on 4x6 inch cards. We use a Dell b1260dn printer.
* A Google email account
* A basic text editor

First, go to this Google spreadsheet while signed in to your Google account: https://docs.google.com/spreadsheet/ccc?key=0Ark-PJD-Ze_DdE1jTFJQMktYQk12UC1EeWk3eXl4dnc

Under file, click "Make a Copy." Give it a name. Voila, you now have a copy in your Google docs

After you've given yourself a version of the Google doc, you need to share it. At the bottom, change the name of the sheet to "cards," minus the quotes. Then click File and Publish To the Web. At the bottom, you will receive a link. Copy that.

Open up story-carder.html and replace the URL listed on line 34 with yours. Save it.

Then open up story-carder.html in a web browser. Kapow, now you have something you can print.

When you click print, be sure to turn margins to none (usually it's set to default) and uncheck Headers and Footers. It should then print your cards in a wonderful fashion.
