# Orca_Bucket
 Repo to contain python automation script to convert CSV files from Splunk Orca reports, to usable Excel reports and deposit in the LoB Folder


 Current implementation: 
 Create a file in the downloads and call it "Orca reps"
 update that file with the CSV's you want to convert. 
 make sure you are in the same directory of the project "/Users/xXx/downloads/orca_bucket/Orca_bucket"
 then run "python3 main"
 rinse and repeat


Adjustments to consider to use this: 
Change the "directory_path = '/Users/xXx/downloads/Orca reps' / output_directory = '/Users/xXx/downloads/Orca reps'" to your own user locations. 



Future Adjustments:
Detect whenever the scan is run and a CSV file is deposited in the folder and automatically do the operation / OR / Immediatly take the CSV file from splunk and convert it then do the below. 
Detect the LoB tag, and compare it with the files in the sharefolder, then deposit it in the Orca file in the scan_results/Orca path. 
