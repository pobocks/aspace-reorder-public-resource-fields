# ASpace Field Reordering Plugin

This is a plugin to enable reordering fields on the ArchivesSpace resource page.

Right now it's very crude - it consists of a single file Ruby view template file, which has to be
manually edited to change the order of fields.  

To install in ArchivesSpace, download the project, edit the file (public/views/records/resource.html.erb) and follow the 
directions [here](https://github.com/hudmol/archivesspace/blob/master/plugins/PLUGINS_README.md) to install it, then restart ArchivesSpace.
