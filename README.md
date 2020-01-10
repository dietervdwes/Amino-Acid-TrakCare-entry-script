# Amino-Acid-TrakCare-entry-script
An AutoHotkey script which reads lines from CSV, parses it and saves the results extracted to various variables.
This script is used to automatically transcribe results from a CSV (for plasma amino acids) and/or insert the standard normal amino acid 
comment for the respective tests.
How to use:

# For Plasma amino acids:
Copy the quantified amino acids CSV file from the GCMS pc onto a flash drive.
Rename the CSV to "aa". (File name should thus be "aa.csv")
Remove the previous aa.csv file in this folder, by either renaming or deleting.
Copy and paste the new aa.csv file into this folder.
Run the SCRIPT called AA (Green Icon).
Log-on to TrakCare and open Result Entry Window.
On the script GUI at the right-hand bottom of the screen click "Plasma_AA".
Let it do the job.
Hit "ESC" on the Keyboard if things go haywire, and then call Dieter to troubleshoot: 082 861 2093, or dieter.vdwesthuizen@nhls.ac.za

# For Urine Amino acids:
No specific results will be entered for urine amino acids and the standard "amino" comment will be inserted for each episode in 
the work list.
It works slightly different than the plasma amino acids in that it doesn't need to read any CSV file and instead just does the 
same repetitive steps to enter the standard comment.
It does need you to have entered the worksheet code and number in result entry window, click find and then open the first episode.
When on the first episode, click the button Urine_AA.
Let it do the job.
Hit "ESC" when an error appears.

# Important:
Note that you can Hit "ESC" at any point if you notice something abnormal is happening and it should stop doing what it is doing 
and reload the script automatically.

# Advanced settings:
The script can be edited with Notepad or ideally Scite4AHK. (Right click and open with... Scite).
The delays between steps can be altered by increasing or decreasing the "sleep, xxxx" values, which are in milliseconds.
Generally by increasing the sleep (wait) time between steps, most errors can be resolved.
The language is AutoHotkey language and the script is also ran by AutoHotkey (currently located in /Documents folder).

Enjoy
Dieter van der Westhuizen
