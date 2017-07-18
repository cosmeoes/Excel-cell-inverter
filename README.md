# Excel-cell-inverter
A python script to invert the cells of an Excel spreadsheet.

NOTE: requires the openpyxl module.


# Usage 
``` python cellInverter.py [file] ```


Or :


``` python cellInverter.py [file] [outputfile] ```

Where [file] is the path (or name) of the file to invert and [outputfile] is the path (or name) of the output file to be created (or overwritten). If no [outputfile] is given the output file wil be saved as 'Inverted[file]' in the current working directory.

For example:

``` python cellInverter.py example.xlsx ```

This will create a file named Invertedexample.xlsx with the data of example.xlsx but inverted (rows are now columns and vice versa).

If instead you use:


``` python cellInverter.py example.xlsx output.xlsx ```


The script will create a file named output.xlsx in the current working directory the data of example.xlsx but inverted (rows are now columns and vice versa).

