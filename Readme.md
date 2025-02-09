# README: Process and Combine DBLP Data

## Overview
to obtain the csv file (output_filtered_complete.csv), we have to processes a large JSON dataset (`dblp.v12.json`), filter and formatsit, and outputs the results into CSV segments. Finally, we combine all segments into a single `output_filtered_complete.csv` file.

## Steps

1. **Prepare the environment**:
   - Ensure you have the necessary libraries installed:
     ```bash
     pip install pandas ijson
     ```

2. **Run the script**:
   - Execute the notebook to process and filter the data from `dblp.v12.json`:


3. **Handling segments**:
   - The script processes the JSON data in segments of 1,000,000 lines.
   - For each segment, it outputs a file named `output_filtered_segment_<segment_number>.csv`.

4. **Combining segments**:
   - After processing all segments, you can combine them into a single file (`output_filtered_complete.csv`) by answering 'y' when prompted.

5. **Final output**:
   - The script will produce a single CSV file: `output_filtered_complete.csv`.



the main code of the algorithms and exploration is in the `main.ipynb` notebook.