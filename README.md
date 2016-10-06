# Asset Pipeline

##What I Learned
I learned that the asset pipeline allows me to import all of my file dependencies and link them appropriately just by requiring them in the right files (usually the application file in a specific directory). The asset pipeline seems to look at the entire tree of files in the Rails app and finds the one being referenced. The most important thing is to require files in the right order. If you require a file in the wrong order, the website won't render properly.

##How I Will Use These Tools Later
I will most definitely be using the asset pipeline in future projects to utilize files like UI frameworks (i.e. Bootstrap), as well as to link my custom files (i.e. my Javascripts and custom CSS) to the application files.
