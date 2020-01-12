# CLHS subchapter consolidator

This is a small tool to consolidate the subchapters of a given chapter in the Common Lisp Hyper Spec.

The Clhs has a different webpage for each (sub-) chapter, even if the contetn is jsut one single line of text... This might have made sense in the early days of the internet, when broadband wasn't available, but today it just makes the thing unreadable. 

This tool recursively follows all the chapterlinks of the given chapter and its subchapters and consolidates them into a single HTML file for better readability.

### How to use
As of right now this tool is contained in an ipython notebook. The last entry contains the code to run it. Simply change the link to the chapter you want to consolidate and run it.

The output is stored in the file specified. The "clhs.html" file contains some sample output.

#### Todo:
Create a python script file from the ipython notebook, that can be used from the command line. The needed parameters are a link to the chapter to be consolidated, as well as an output file.