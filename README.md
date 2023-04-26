# active_incident_resource_summary_report
This is a Python program that extracts tables from PDF files and saves them as CSV files. The program uses the tabula library to extract tables from PDF files, the pandas library to manipulate the data, and the tqdm library to show a progress bar.

The program works on a folder containing PDF files and saves the extracted tables as CSV files in a separate folder. The PDF files should have a specific name format with the date in the format of "YYYY_MM_DD".

The program loops through each PDF file in the folder, extracts the table(s) from the PDF using tabula, adds the date to the table as a new column using the pandas library, and saves the table as a CSV file in the output folder.

The program also includes error handling to check if the output folder exists and create it if it doesn't exist. Finally, the program outputs "Done!" to the console when it has finished processing all the PDF files in the input folder.
