Fork of the Gold Parser Builder java implementation.

The only work I've done is change the build system from Ant to Maven.

One unit test was failing b/c it looks for the text of a specific Exception (which may change from OS to OS or from one minor version of Java to the next...).  I've fixed that for my OS and Java implementation.

The grammars directory is currently duplicated in two places because in some of the code it loads the files as files from the file system and in other places it loads them via the class path (which differs from Ant to Maven).  Hopefully I'll find the energy to fix this some day.

If you have any bug fixes please submit them to the upstream project and if they are accepted they will eventually trickle down to this project.


