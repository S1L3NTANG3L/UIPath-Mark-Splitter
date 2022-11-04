# UIPath-Mark-Splitter
Tiny UIPath automation process I wrote to take the given markschema and create an individual marksheet for each student and print it to there feedback folder.</br>
## Using Steps
1. Note down the sheet names of both the mark schema spreadsheet and template spreadsheet
* NB The sheet name is case sensitive
2. Make sure the template will print correctly before starting the process.
3. Run the process.
4. First option is discord webhook integration, handy for longer processes.
5. Choose the mark schema excel file.
6. Enter its sheet name.
7. Choose the mark template excel file.
8. Enter its sheet name.
9. Choose the mode of operation.
* Assignment mode is for when you have a dropbox style file structure such as the one given when you batch download from efundi or plan to print to the site       dropbox. 
* Other mode gets used when you want to print all the files to the root directory. 
* Dropbox mode gets used if you plan to have the files print to the student dropbox folder on the site. Note You will need to have efundi already logged in and the dropbox link ready to be copied.
10. If you chose the dropbox mode it will ask you for the link to your dropbox site.
11. If you chose the dropbox mode it will ask you for a grades or report spreadsheet, this will be used to get the student's first and last name using there student number for later processes.
12. Enter the filename prefix, leave the textbox empty is not needed and press ok , output format if something is entered ->    prefix-studentnumber.txt
13. Choose the root folder that either contains all the individual student folders or the appropriate folder if other mode chosen earlier.
14. Process will now start up and run in the background.
15. If discord integration was chosen you will get a notification when it is done.
