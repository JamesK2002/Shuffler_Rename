# Shuffler_Rename
Final task CSCI 310 : Avatar

Problem: 
- output file naming convention is long/redundant
- includes category identifier despite being in category folders
- includes timestamp which is included with parent folder

Desired outcome:
- simple file names: 1.csv, 2.csv, 3.csv, etc.
- implement changes in the output directory after the files have been created
- rename files in random order, sequentially from 1 to N
- when a new file is created, the system must know what N+1 is
- new file is named N+1
- N = number of files already present