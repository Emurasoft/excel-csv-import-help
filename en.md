# CSV Import+Export Help Page

## Import CSV

The Import CSV pane contains options for importing CSV data to your workbook.

Here is a sample CSV text to test out the app:

```
name,size
delimiter.png,2553
encoding.png,2216
importType.png,7640
newlineSequence.png,2544
```

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/importType.png?raw=true" width="350px" />

1. Import type dropdown and input

    Import type is the import source. You can upload a file or select "Text input" to copy and paste the CSV as text.

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/encoding.png?raw=true" width="350px" />

2. Encoding dropdown

    Most files will be imported correctly with Auto-detect, but you may have to select the correct encoding if the imported text is not correct. This dropdown is available if Import type is File.

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/delimiter.png?raw=true" width="350px" />

3. Delimiter dropdown

    Delimiter is the field separator, which is typically a comma. Select "Other" to input a custom delimiter.

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/newlineSequence.png?raw=true" width="350px" />

4. Newline sequence dropdown

    Newline sequence is the record separator. Auto-detect will most likely be able to figure it out.

5. Import CSV button

    Click Import CSV to start importing using the above options. If the current worksheet is blank, the imported data is added the the current worksheet, otherwise the data is added to a new worksheet.

6. Save options toggle

    If Save options is on, all Import CSV and Export CSV options are saved automatically.

## Export CSV

The Export CSV pane contains options for exporting the current worksheet to CSV. 

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/exportType.png?raw=true" width="350px" />

1. Export type dropdown

    Choose between downloading the exported CSV file or copying the result from a text box. The File option is disabled on Excel for Mac and Excel for iPad because the save as dialog box does not appear on those platforms.

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/encoding.png?raw=true" width="350px" />

2. Encoding dropdown

    This is the encoding of the output file.

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/delimiter.png?raw=true" width="350px" />

3. Delimiter dropdown

    Delimiter is the field separator, which is typically a comma. Select "Other" to input a custom delimiter.

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/newlineSequence.png?raw=true" width="350px" />

4. Newline sequence dropdown

    Newline sequence is the record separator. The most commonly used on Windows is CRLF, while macOS and Linux uses LF.

5. Export to CSV button

    Click Export to CSV to export the current worksheet using the above options.

6. Save options toggle

    If Save options is on, all Import CSV and Export CSV options are saved automatically.

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).