# LaTex-Formatting
Provides .sty, .bst, and .cls files commonly used for proposal and paper preparation within my research group.

The files in here are consolidated Latex commands that we found ourselves using repeatedly for proposals and scientific publications, so putting them here makes them easily retrievable from Overleaf (and prevents us from having to continually write, from scratch, our LaTex preambles!)

There are 2 different kinds of files in here:  

(1) the "AAS" document class files.  Some time ago, I modified aastex631 to have some additional functionality.  That style file is now outdated and should not be used for new publications to be submitted to ApJ and AJ, but is perfectly fine to use for other applications (like proposals).  Other files go with that style file, like the .bst, etc. 

(2) a more general class file, where one uses the following commmand:  \documentclass{article}. The other associated .sty files are similar to those that accompany the above aas-style file, but may have some additional explicit \usepackage commands that are needed for the WorPT tables but inherent when using the aas style file. 

