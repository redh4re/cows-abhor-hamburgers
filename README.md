# Cows Abhor Hamburgers
Cows Abhor Hamburgers is an unofficial expansion for
[Cards Against Humanity](http://cardsagainsthumanity.com). These templates
can be used to create custom cards that are suitable for professional
printing.

The resulting cards are 2.5 x 3.5 inches. The template includes margin and
bleed areas to ensure all text appears on the final card.

## Required font
The "Neue Helvetica® Std 75 Bold" font is used to match the Cards Against
Humanity style as closely as possible. The font can be purchased from
linotype: http://www.linotype.com/45470/NeueHelveticaStd75Bold-product.html.

## Creating cards
The card content was originally created in Google Docs as a shared spreadsheet.
Once all cards are written the black and white cards must be exported as
seperate CSV files. Each CSV file must have a "CardText" header row for the
DataMerge to function.

If your cards contain have any special characters (such as © or ®) then you
should confirm the CSV exported correctly.

* Open the appropriate template using Adobe InDesign CC.
* Click Window → Utilities → Data merge
* Click the Menu icon in the upper right of the Data Merge window
* Click "Select Data Source..."
* Navigate to your exported CSV and click Open
* Click the "Create Merged Document" icon in the bottom right of the Data Merge window
  * Ensure "All Records" is selected
  * Ensure "Records per Document Page" is set to "Single Record" 
* Click OK
* A dialog showing "No overset text was generated when merging records." should appear, click OK

The pages list should now have a page per-card you created! At this point you
should verify the layout of each card; it's common to change the size of the
blank space for black cards.

## Export the cards as a PDF
The cards should be delivered to the printing company as a multi-page PDF.
To export the pages from InDesign you should:

* Click File → Export
* Change the "Save as type" to "Adobe PDF (Print)"
* Enter a filename
* Click Save
* Select "[High Quality Print]" from the "Adobe PDF Preset" dropdown
* Go to the Compression section
  * Set Compress to None for Color Images, Grayscale Images, and Monochrome Images
  * Uncheck "Compress Text and Line Art"
* Go to the Marks and Bleeds section
  * Check "Use Document Bleed Settings"
* Click Export
