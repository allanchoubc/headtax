# headtax
Chinese Canadian Headtax Project
This dataset was based off of the original dataset on Open Collections UBC: 
https://open.library.ubc.ca/cIRcle/collections/facultyresearchandpublications/52383/items/1.0075988

The changes include: 
Two newly added column: HEIGHT-IN-CONVERT, HEIGHT-REVISED 
HEIGHT-REVISED converted the original HEIGHT_FT and HEIGHT-IN into a numeric(inches), a format that allows for easier manipulation and analysis. 

Demystefication of a few key variables:
Formalized county name: New_County
Formalized village name: MatchCH_ID   0 means missing data 
ViLL_ID is not normalized, but rather the various transliterations of villages.
Formalized destination: New_Dest, Dest_code 
