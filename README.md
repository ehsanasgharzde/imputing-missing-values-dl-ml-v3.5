# Missing Value Imputation Program (Version 3.5)

This program is designed to perform missing value imputation on a dataset using various Machine Learning (ML) and Deep Learning (DL) methods. The program reads a dataset from an Excel file, handles multivariate imputation, and saves the imputed dataset to a CSV file. Below are the details of how to use the program.

## Usage Instructions

1. **Prerequisites:**
    - Python 3.x
    - Required Python libraries (make sure to install them using `pip` if not already installed):
        - pandas
        - seaborn
        - scikit-learn (sklearn)

2. **Data Preparation:**
    - Ensure you have your dataset in the `clean-xls-files` directory as an Excel file named `AMR-and-NSH-Buoy-Data1394-Clean-Data.xls`. Make sure the file path is correctly specified in the `main.py` script.

3. **Running the Program:**
    - Open a terminal or command prompt.
    - Navigate to the directory containing `main.py`.

4. **Execute the Program:**
    - Run the program by executing the following command:
      ```python main.py```

5. **Imputed Data Output:**
    - The program will perform missing value imputation using Support Vector Regression (SVR) and create a new dataset with imputed values.

6. **Results:**
    - The imputed dataset will be saved as a CSV file named `AMR-and-NSH-Buoy-Data1394-normalized-mice-svr.csv` in the `multivariate-method-results` directory.

7. **Data Analysis:**
    - The program also performs data analysis on the "Buoy Amirabad Battery Voltage(1)" column and plots a distribution graph. The resulting plot will be displayed on the screen.

8. **Customization:**
    - You can customize the ML/DL methods or parameters used for imputation by modifying the `main.py` script. For example, you can change the estimator (SVR) to other ML models like Decision Trees or Extra Trees.

9. **Version Control:**
    - This is Version 3.5 of the program, which uses SVR for imputation. You can refer to previous versions if needed.

10. **Feedback and Support:**
    - If you encounter any issues or have questions, feel free to reach out for assistance.

Happy imputing!
