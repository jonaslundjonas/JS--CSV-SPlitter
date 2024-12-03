CSV File Splitter
Written by Jonas Lund, 2024

Description
This web application is designed to split CSV files into multiple smaller files while preserving the header row in each part. It's ideal for breaking down large CSV files into more manageable chunks.

Instructions
Upload your CSV files by either dragging and dropping them into the designated area or clicking to select them from your computer
Enter the number of parts you want to split each file into (minimum 2)
Click the "Split Files" button to process your files
Each split part will automatically download to your computer
Expected Output
For each CSV file, you'll receive multiple files named '[original_filename]_part_X.csv'
Each part will contain an equal portion of the rows from the original file (±1 row due to rounding)
All split files will include the original header row
The application will display the number of rows in each split file
Features
Supports multiple file processing at once
Preserves CSV formatting and header rows
Works entirely in your browser - no data is sent to any server
Handles large files efficiently
Compatible with all standard CSV files
