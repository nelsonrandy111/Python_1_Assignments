# Assignment 5: Annotation Analysis and Serialization

This project focuses on analyzing satellite annotation files using Python. The tasks involve counting annotations, organizing them into structures by month and year, and serializing these structures using JSON and Pickle formats. Additional tasks include working with datetime objects and sorting annotations chronologically.

## Project Overview

The annotation files follow a naming convention and are analyzed using pattern-matching techniques. The tasks covered in this project include:

1. **Annotations by Month and Year**: Counting annotations to identify which month has the highest number of files.
2. **Organizing Annotations**: Creating a dictionary where:
   - Each key is a month (e.g., "July 2024").
   - Each value is a list of annotation file names or dictionaries with additional metadata.
3. **Serialization**:
   - Saving the dictionary in JSON and Pickle formats.
   - Reloading the serialized data to validate the integrity.
4. **Datetime Integration**: Adding datetime objects to the data structure for richer metadata.
5. **Sorting Annotations**: Printing all annotations from the second half of 2024, sorted from the oldest to the newest.

## Analysis Tasks

### Task 1: Count Annotations by Month and Year
- Parse annotation file names to extract the date, then count how many annotations exist for each month and year.
- Identify the month with the highest number of annotations.

### Task 2: Create a Dictionary of Annotations by Month
- Organize annotations into a dictionary where the key is the month, and the value is:
  - A list of file names.
  - Alternatively, dictionaries containing the file name and corresponding date.

### Task 2 a and b: Serialization
- Save the annotation dictionary in JSON format and reload it to verify correctness.
- Save the dictionary using Pickle for more efficient storage and reload it to verify correctness.

### Task 3: Sort Annotations for the Second Half of 2024
- Extract annotations from July to December 2024 and sort them chronologically by date.
- Print annotations in ascending order of their creation date.
- In the example case, there are no file in the second half of the year.

## Project Structure

- **`Assignment_5.ipynb`**: The Jupyter Notebook file containing the code for analysis and serialization tasks.

## Prerequisites

Ensure you have the following Python libraries installed:
- `os`
- `glob`
- `re`
- `json`
- `pickle`
- `datetime`

## Usage

1. Place the annotation files in the specified directory (e.g., `session_4/annotations`).
2. Open and execute the cells in the `Assignment_5.ipynb` notebook.
3. Review the outputs for insights on annotation counts, serialized data, and sorted lists.

## Outputs

- **Annotations per Month and Year**: A summary of annotation counts.
- **Serialized Files**: Two files, `json_annotations.json` and `annotations_by_month.pkl`, saved in the working directory.
- **Sorted Annotations**: A list of annotations from the second half of 2024, displayed in the console.
