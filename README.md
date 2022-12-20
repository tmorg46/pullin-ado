# pullin-ado
A command that replicates a many-to-one merge with keep(1 3) and nogen options in fewer characters.

---------------------------------

The following commands are therefore equivalent:

**merge m:1** _varlist_ **using** _filename_**, keep(1 3) nogen**

**pullin** _varlist_ **using** _filename_


---------------------------------

available to install from the SSC! via
**ssc install pullin**

honestly, I just got tired of typing m:1 , keep(1 3) nogen for every single merge I ran in the Record Linking Lab, so here's this
