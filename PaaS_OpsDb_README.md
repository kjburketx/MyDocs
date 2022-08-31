# PaaS\_OpsDb\_README.md


## Version References
- Versions will be in format of "<major>.<minor>.<patch>
- Major level _may_ change the ordering of columns -or- CAML ID
- Minor version will be used to add columns -or- resolve data type collisions  
- Patch - errata only

## File Structure  
- Basic data format: UTF-8 8bit, CSV (Comma Separated Values)  
- Column separators shall be commas - ","
- Columns shall not be fixed width
- First row shall ALWAYS be a header row
- First row shall NOT be started with a "#" 
- First column shall always be the CAML-style variable ID
- Second column shall always be the variable value
- Inter-field value separators shall not use commas - ","
- 

## Value Types
- CHAR:Character:Variable length
- INT: Interager:64bit
- Float:


## Data Schema:

| CAML ID | Value | Value Type |  Description |
| ------------ | -------------- | ------------------ | ---------- | 
|1| | | | 