
# README: Assignment 7 - Data Manipulation with Pandas

---

## **Project Overview**

Assignment 7 focuses on data manipulation tasks using the Pandas library in Python. The exercises involve creating new columns, combining DataFrames, and extracting specific information using string operations. The primary goal is to enhance data structuring and querying skills.

---

## **Project Tasks**

### **Task 1: Create a Column for Professor Initials**
- Generate a new column named `professor_initials` that stores the initials of each professor's first and last name.
- Input DataFrame includes:
  - `professor`: Full names of professors.
  - `department`: Their respective departments.
  - `age`: Their ages.

### **Task 2: Combine DataFrames Using `join`**
- Use the given `df_courses` DataFrame that associates professors with the courses they teach.
- Combine `df` and `df_courses` using the `join` operation based on the `professor` column.

### **Task 3: Merge DataFrames**
- Merge the original `df` and `df_courses` DataFrames to create a single DataFrame containing all relevant information about professors, their departments, and the courses they teach.

### **Task 4: Extract Professor Last Names**
- Create a new column `professor_last_name` by extracting the last name of each professor using string operations on the `professor` column.

---

## **Project Structure**

- `Assignment_7.ipynb`: Jupyter Notebook containing the exercises and their implementations.
- **DataFrames Used**:
  1. `df`:
     - Columns: `professor`, `department`, `age`
  2. `df_courses`:
     - Columns: `professor`, `courses`

---

## **Usage Instructions**

1. **Prerequisites**:
   - Ensure you have Python installed with the Pandas library (`pip install pandas`).

2. **Steps to Run**:
   - Open the `Assignment_7.ipynb` file in Jupyter Notebook or an equivalent environment.
   - Execute the cells sequentially to complete all tasks.

3. **Expected Outputs**:
   - A DataFrame with an additional `professor_initials` column.
   - A combined DataFrame containing professors' details and courses.
   - A DataFrame with a new column `professor_last_name`.

---

## **Outputs**

- **Final DataFrame**:
  - Columns: `professor`, `department`, `age`, `professor_initials`, `courses`, `professor_last_name`
- **Insights**:
  - Extracted initials and last names for better readability.
  - Integrated courses information with the main DataFrame.

---

## **Additional Notes**

- String operations and Pandas merging techniques are crucial for efficient data manipulation.
- Modify file paths or data as needed to suit your environment.

---

This README serves as a guide to execute and understand the exercises in Assignment 7.
