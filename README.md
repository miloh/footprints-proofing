footprints-proofing
-------------------

the goal of this project is to automate the export of batches or libraries of
footprints of questionable origin onto a gridded project, add silk descriptions
for the parts, and to print out paper copies for size & fit of the footprints.  

first commits will be doing the process manually in pcb.  

development
-----------
[gaf-footprints](https://github.com/miloh/gaf-footprints) is the original
source, but the project should be agnostic and allow user to not only process
footprints for output and manual comparison, but eventually allow for
discrepancy checking against footprints.  geda pcb's automated method of
overwriting files with the geda pcb file format, normally annoying when it removes
useful comment or reference material from footprint files, may come in handy
here.  

