# UIPath-Mark-Splitter
Tiny UIPath automation process I wrote to take the given markschema and create an individual marksheet for each student and print it to there feedback folder.</br>
## Using Steps
*WARNING! The process will kill any running excel process when you click start!
1. Note down the sheet names of both the mark schema spreadsheet and template spreadsheet
* NB The sheet name is case sensitive
2. Enter the markschema sheet name, Rubric template sheet name.
3. Enter a filename prefix (optional) => 'prefix - studentnumber.pdf'
4. Enter the discord webhook (optional)
5. Choose the mode of operation.
* Assignment mode is for when you have a dropbox style file structure  such as the one given when you batch download from efundi or plan to  print to the site       dropbox.
* Other mode gets used when you want to print all the files to the root directory.
* Dropbox mode gets used if you plan to have the files print to the  student dropbox folder on the site. Note You will need to have efundi  already logged in and the dropbox link ready to be copied.
8. Click run
9. A open file dialog will appear, use it to open you markschema.
10. A second open file dialog will appear, use it to open the rubric template.
11. Choose the root folder that either contains all the individual  student folders or the appropriate folder if other mode was chosen earlier.
12. Process will now start up and run in the background, a completion dialog will appear in the top left corner to keep you up to date with the current progress.
### UI
![UI](https://user-images.githubusercontent.com/37051908/203733263-1a42576d-7b2b-4432-b3f4-77e8d3caed8c.png)
### Choose Markschema
![Choose MarkSchema](https://user-images.githubusercontent.com/37051908/203733314-f221d10f-9a5c-45aa-999c-cca2d8009fcb.png)
### Choose Template
![Choose Template](https://user-images.githubusercontent.com/37051908/203733393-69cfb975-12c3-4243-87b4-9122f7388eae.png)
### Choose Output Folder
![Choose Output Folder](https://user-images.githubusercontent.com/37051908/203733444-7782db84-cf1a-4527-b4fe-d818df3b0785.png)
### Current Status
![Current Status](https://user-images.githubusercontent.com/37051908/203733653-b677122c-4f02-4a5d-aa3e-f102a8ad2e3f.png)
