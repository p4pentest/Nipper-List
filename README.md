# Nipper-List

This script does configuration review (using Nipper) in an excel file.

Make three folders as below

Firewall - containing all firewall configuration files

Switch - containing all switch configuration files

Router - containing all router configuration files

Extract the ZIP file.

EDIT THE FILE 'nipperlist' :

CHANGE THE BELOW LOCATION WITH THE NEW LOCATION OF THE FILE 'General_Nipper_Review_Report_26-11-2015.xlsx'

/home/Scripts/Nipper_List/General_Nipper_Review_Report_26-11-2015.xlsx

Go to the script location

./nipperlist

[provide full path of any folder(firewall, switch or router)]

[select appropriate option]

Look for the csv format file "Config_Review_Report.csv" in the location of the [config files folder]/Nipper_Output/Nipper_CSV_Output

Look for the "ErrorLog" file and check if any vulnerability of an IP is missing in the csv file. Add that manually in the CSV file.

Also add the same in the file "General_Nipper_Review_Report_26_11_2015.xlsx" in the same folder as the script. For all future reports this upated list will be considered.
