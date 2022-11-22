# UIPath-Mark-Splitter
Tiny UIPath automation process I wrote to take the given markschema and create an individual marksheet for each student and print it to there feedback folder.</br>
## Using Steps
Using Steps
1. Note down the sheet names of both the mark schema spreadsheet and template spreadsheet
* NB The sheet name is case sensitive
2. Enter the markschema sheet name, Rubric template sheet name.
3. Enter a filename prefix (optional) => 'prefix - studentnumber.pdf'
4. Enter the discord webhook (optional)
5. Choose the mode of operation.
* Assignment mode is for when you have a dropbox style file structure  such as the one given when you batch download from efundi or plan to  print to the site       dropbox.
* Other mode gets used when you want to print all the files to the root directory.
* Dropbox mode gets used if you plan to have the files print to the  student dropbox folder on the site. Note You will need to have efundi  already logged in and the dropbox link ready to be copied.
6. If you chose the dropbox mode it will ask you for the link to your dropbox site.
7. If you chose the dropbox mode it will ask you for a grades or report  spreadsheet, this will be used to get the student's first and last name  using there student number for later processes.
8. Click run
9. A open file dialog will appear, use it to open you markschema.
10. A second open file dialog will appear, use it to open the rubric template.
11. Choose the root folder that either contains all the individual  student folders or the appropriate folder if other mode was chosen earlier.
12. Process will now start up and run in the background, a completion dialog will appear in the top left corner to keep you up to date with the current progress.
![UI](https://i.imgur.com/A6n6BoD.png)
