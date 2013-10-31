Latex template for all kind of theses at TU-Berlin 
--------------------------------------------------
(**D**iplom **A**rbeits **La**tex **Te**mplate)

### [history]
* based on Latex Makefile from [Chris Monson](http://www.bouncingchairs.net/oss) 2004 (shiblon@gmail.com)


### [usage]
* clone the git tree to your local system where a standard latext evn ist required
* just do a "make" to create the output file: master.pdf
* to renew your complied pdf trigger a "make clean" to earase all potential outdated compiled file
* to mofify, add or delete the document structure or esthetic, please edit the master.tex file as you need it
* put all you bibtex library files into the subfolder ./bibliography/ & add them to master.tex as required
* the Makefile originally from Chris Monson is extended by the feature to include R scripts that got compiled create a plot on the fly into the pdf (thx to N. Sarrar)

### [TODO]
