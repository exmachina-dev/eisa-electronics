    
      ______ _     _              _           _                   _          
     |  ____(_)   | |            | |         | |                 (_)         
     | |__   _ ___| | __ _    ___| | ___  ___| |_ _ __ ___  _ __  _  ___ ___ 
     |  __| | / __| |/ _` |  / _ \ |/ _ \/ __| __| '__/ _ \| '_ \| |/ __/ __|
     | |____| \__ \ | (_| | |  __/ |  __/ (__| |_| | | (_) | | | | | (__\__ \
     |______|_|___/_|\__,_|  \___|_|\___|\___|\__|_|  \___/|_| |_|_|\___|___/
                                                                         
                                                                         
Eisla electronics
#################

This repo contains all necessary files to design and produce PCBs for the Eisla product range.

File format and folder structure
################################

Documentation files should be in PDF. Board image files can be in PNG or PDF
PCB Design file are in EAGLE Standard edition (7.4) file format.

These are general rules to help maintain a consistent folder structure:
- All libraries are placed inside the root lib/ folder.
- One board for each project folder.
- Mutiples revisions can be placed inside a subfolder. i.e. ArmazCape/Rev A1
- BOMs, partlists, spreadsheet should placed inside a BOMs/ folder.
- Documentations files are in eagle-resources/doc or in doc/ inside a project folder.