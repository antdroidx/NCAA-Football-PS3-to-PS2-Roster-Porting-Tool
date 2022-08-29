##NCAA Football PS3 to PS2/PSP Conversion Tool

Created by Anthony Nguyen

http://www.AntDroid.dev


This tool was created to help assist in the conversion of an extracted NCAA Football roster from the Playstation 3 system to create a CSV file that can be used to create a roster file for the NCAA Football series for Playstation 2 and Playstation Portable.


To download, press CODE, and Download Zip in the drop down menu at the top.


Updates:

v0.70 - Dec 12, 2021

+Complete Re-Balance of Attributes to closer match NCAA 06 original database

+Accurate Overall Rating Calculations


v0.60 - Dec 08, 2021

+Fixed name capitalizations

+Added more Head/Hair combos

+Fixed Macros



Requirements:

* Microsoft Excel
* A PS3 Roster
* PS3 BruteForce Save Data
* NCAA Dynasty Editor or EA Generic Editor
* Madden DB Editor v2.0 or v3.0 or Madden Xtreme Editor


Creating a PS3 Import CSV
1. Extracting a PS3 save from a save archive using BruteForce Save Data application.
2. Open the PS3 save in NCAA Dynasty Editor.
3. Click the Players tab (any of them) and click export to CSV once it’s loaded.
4. Rename this cvs file to PS3_Input.csv and place in the same folder as the conversion
tools.


Conversion Tool

VERY IMPORTANT - Open the tool in this exact order otherwise you’ll have errors.

1. Open the PS3_Input.csv file you just created in Excel.
2. Open NCAA_PS3_Conversion.xlsm
3. Follow the instructions inside - i.e. press CTRL+SHIFT+N or Command+Opt+Shift+N
to start a macro that runs a name conversion tool. Press OKAY when prompted (twice?)
4. Once finished, open OUTPUT tab.
5. Press CTRL+SHIFT+R or Command+Opt+Shift+R to enable the macro to fill the
roster.
6. This could take a while…
7. Once finished, scroll down and delete any extra rows that show up at the bottom.

8. Please also delete all PGID (Player IDs) from:

NCAA 05 through NCAA 08 FBS Rosters

12670 to 16029

16170 to end



NCAA 09-11 FBS Rosters

12670 to 12739

15260 to 16029

16170 to end


9. Save as CSV.




Importing to PS2/PSP
1. Open your PS2 or PSP save file in Madden DB Editor.
2. Click the PLAY table and load it up. It will take a while.
3. Once loaded, go to IMPORT, then import the csv you just created.
4. Save and you’re all done!
