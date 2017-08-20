# V3_Hardware_Design_Files
Contains files created with Design Spark PCB Capture Software

# Installation
Design Spark is a free PCB design software available for download here
http://www.rs-online.com/designspark/electronics/eng/page/designspark-pcb-home-page

Download and install the Design Spark software (Windows based), then follow the instructions below to view, modify, etc.

The OpenBCI board suite uses many custom components that we've designed in Design Spark.
In order to use the design files to their fullest extent, you must add the files contained in the Design Spark Libraries folder to the following location:

    Users\Public\Documents\DesignSpark PCB 7.0\Library\User

Then, fire up Design Spark! If this is your first time running Design Spark, you will need to enable the Library folder first thing. When Design Spark opens, open the Libraries pane by clicking File, Libraries (Cntrl+L). When it opens, click on the Folders tab and select

    C:\Users\Public\Documents\DesignSpark PCB 7.0\Library

Then click the 'Folder Enabled' radio button.

Now when you open the .sch and .pcb files, you can modify to your hearts delight!

# Improperly Designed Pin on Daisy Module

* as per this page http://openbci.com/community/daisy-module-re-work/
* error in PCB design

# Gerber Files

* gerber files can be found for the 32bit, Daisy, and dongle boards in their respective subdirectories
* file extensions of the gerber files were changed to those compatible with many board houses (note the file extensions vary from board house to board house)

# Bill of Materials

* as per the [OpenBCI docs page](http://docs.openbci.com/Hardware/02-Cyton):
    * resistors are thin film
    * capacitors are MLCC X7R
    * battery connector is standard JST type two position (with polarity key at top)
    * SD card holder used is [ST-TF-003A](https://octopart.com/st-tf-003a-suntech-29424852)
* combined bill of materials for 32bit, Daisy, and dongle boards is in the the "BOM_combined.ods" spreadsheet (open document format)
* for many (but not all) of the parts a digikey product ID & estimated price can be found
* please note these part numbers or costs may not be accurate

# License Information

All contents of this repository are released under [Creative Commons Share-alike 3.0](http://creativecommons.org/licenses/by-sa/3.0/).
