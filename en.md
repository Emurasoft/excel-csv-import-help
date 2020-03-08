# CSV Import+Export Help Page

## Import CSV

The Import CSV pane contains options for importing CSV data to your workbook.

Here is a sample CSV to test out the app:

```
name,size
delimiter.png,2553
encoding.png,2216
importType.png,7640
newlineSequence.png,2544
```

1. Import type dropdown and input

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/importType.png?raw=true" width="350px" />

You can upload a file or select "Text input" to copy and paste the CSV as text.

2. Encoding dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/encoding.png?raw=true" width="350px" />

Most files will be imported correctly with Auto-detect, but you may have to select the correct encoding if the result does not look correct. This dropdown is available if Import type is File.

3. Delimiter dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/delimiter.png?raw=true" width="350px" />

Delimiter is the field separator, which is typically a comma. Select "Other" to input a custom delimiter.

4. Newline sequence dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/import/newlineSequence.png?raw=true" width="350px" />

Newline sequence is the record separator. Auto-detect will most likely be able to figure it out.

5. Import CSV button

Click Import CSV to start importing using the above options. If the current worksheet is blank, the imported data is added the the current worksheet, otherwise the data is added to a new worksheet.

6. Save options toggle

If Save options is on, all Import CSV and Export CSV options are saved automatically.

## Export CSV

The Export CSV pane contains options for exporting the current worksheet to CSV. 

1. Export type dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/exportType.png?raw=true" width="350px" />

Choose between copying the result from a text box or downloading the exported CSV file. The File option is only available for Excel Online because the "save as" dialog box does not appear on desktop platforms.

2. Encoding dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/encoding.png?raw=true" width="350px" />

This is the encoding of the output file.

3. Delimiter dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/delimiter.png?raw=true" width="350px" />

Delimiter is the field separator, which is typically a comma. Select "Other" to input a custom delimiter.

4. Newline sequence dropdown

<img src="https://raw.githubusercontent.com/Emurasoft/excel-csv-import-help/master/images/export/newlineSequence.png?raw=true" width="350px" />

Newline sequence is the record separator. Windows typically uses CRLF, while macOS and Linux uses LF.

5. Export to CSV button

Click Export to CSV to export the current worksheet using the above options.

6. Save options toggle

If Save options is on, all Import CSV and Export CSV options are saved automatically.

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).