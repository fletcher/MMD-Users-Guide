Title: MultiMarkdown User's Guide
Author:			Fletcher T. Penney  
Date:			July 10, 2009  
Copyright:		2009 Fletcher T. Penney.  
				This work is licensed under a Creative Commons License.  
								http://creativecommons.org/licenses/by-sa/2.5/
								
This project contains various source files that are used to generate the
MultiMarkdown User's Guide. To build the final document(s), first concatenate
the source files into a single MultiMarkdown document:

	mmd_merge index.txt > guide.txt

Use MultiMarkdown to create the output format of your choice:

	mmd guide.txt

will generate `guide.html`.  You can also run `mmd2pdf` if you have LaTeX installed.
	
Please feel free to submit improvements to this document.

