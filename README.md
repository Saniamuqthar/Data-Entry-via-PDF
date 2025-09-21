# Data-Entry-via-PDF
This project shows ways of entering data in Excel from a pdf, without having to use to use any complex formulas of Excel.
## Data Set
- Fictional Estate Planning Council of Cleveland data with 19 rows
- Columns include: Name, Title,	Company,	Street Address,	City,	State,	ZIP,	Phone Number,	Fax Number,	Email,	Website
## Tools Used:
- Microsoft Excel
- Photos (app from PC) 
## Workbook Includes:
- Cleaned Data
- Original / Inconsistent Data
## Data Entry Process
The PDF Screenshot was taken in 3 parts with zoom so that the text can be clearly scanned through photos app on PC. Each Accountant’s information was copied through CTRL + C so that no errors appear at the time of pasting the copied text in Excel. Of course there were errors while copying, for reference, when information of Accountant [ Charles J. Avarello CPA, CFP® ] was copied the cursor also copied the Name and Email of another Accountant [Alane Boffa CPA, Email: aboffa@cohencpa.com ]. So after every Accountant’s information a whole row was left null just so that there is no confusion during data entry.
-	Made a proper header row.
-	Copied every Accountant’s information one at a time.
-	Leaving the cell that contains the Name of the Accountant, copied rest of the cells and pasted them through ‘Paste Transpose’ depending upon the detail of the first copied cell. If it’s a title then pasted on B2 else C2.
-	City, State, ZIP were all combined in the City column and Phone numbers, FAX, Email, Website occupied the rest rows respectively. Clicking on cell of Phone Number, inserted a new row while shifting the rows to the right, and repeated it once again, so that every value in the cell belongs to its respective header.
-	In the blank State column cells, wrote the State name (OH, FL) manually for the first 3 rows and then used Flash Fill from Data Tab to fill rest of the State column. 
-	Same process as above was used again for ZIP column
-	For Phone Number, FAX, Email, Website columns the information came with its ‘header’, so replaced those cells with null for proper formatting.
-	To fill out blanks, selected the whole data -> Home Tab -> Find and Select -> Go To Special -> Blanks -> OK
-	Inserted a Hyphen (-) for all blank rows, and pressed CTRL + ENTER 
-	A recheck was done to see whether the values in cells are matching to the values in PDF and corrections were made.
## Author
- <a href="https://github.com/Saniamuqthar">Author</a>
