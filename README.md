# BookListHandler
A tiny python script to grab the titles from a LibraryThing catalogue for easier inventory

Not sure if this will be useful to anyone else because it uses the particular code that this catalogue used to get the first few lines after (usually the title + the author, sometimes also captures year and start of the tags). However, if the books have ID codes of a different type, it'll still work if you just change the regex. My catalogue used the format ABC A12 to start off each new item.

It was a fun little challenge for me as a complete beginner to Python so I figured I would post it up anyways! 

LibraryThing allows you to download a .pdf version of an entire catalogue. I converted the pdf to txt and went from there to output a simple text file with one title per line.
