```
____ _ ____ _    ____    ____ _    ____ ____ ___ ____ ____ _  _ _ ____ ____ 
|___ | [__  |    |__| __ |___ |    |___ |     |  |__/ |  | |\ | | |    [__  
|___ | ___] |___ |  |    |___ |___ |___ |___  |  |  \ |__| | \| | |___ ___] 
 
```
                                                                         
                                                                         
# Eisla electronics

This repo contains all necessary files to design and produce PCBs for the Eisla product range.

## File format and folder structure

Documentation files should be in PDF. Board image files can be in PNG or PDF
PCB Design file are in EAGLE Standard edition (7.4) file format.

These are general rules to help maintain a consistent folder structure:

* All libraries are placed inside the root lib/ folder.  

* One board for each project folder.  

* Mutiples revisions can be placed inside a subfolder. i.e. ArmazCape/Rev A1  

* BOMs, partlists, spreadsheet should placed inside a BOMs/ folder.  

* Documentations files are in eagle-resources/doc or in doc/ inside a project folder.