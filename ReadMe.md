**ID CARD GENERATOR**

This code can be used to generate ID Cards by using the data given in CSV file.

The properties are given in config.properties file

**config.properties file update**
- **id_template** = Your id template location 
- **csv_file** = THis file contains the data like Name, Position, Photo Location.
- **output_filename** = The output file name with generated ID cards.
- **images_directory** = The folder where the images are stored.

**Commands to activate the venv:**

# Python Virtual Environment Setup

## macOS:

1. **Create Virtual Environment:**
   - Open Terminal.
   - Navigate to your project directory.
   - Run the command:
     ```
     py -m venv venv
     ```

2. **Activate Virtual Environment:**
   - In the same Terminal window, activate the virtual environment by running:
     ```
     .\venv\Scripts\activate
     ```
   - Your prompt will change to show the virtual environment name, indicating that it is now active.

3. **Install Dependencies:**
   - Ensure you have a `requirements.txt` file in your project directory.
   - Install required Python packages by executing:
     ```
     pip install -r requirements.txt
     ```

## Windows:

1. **Create Virtual Environment:**
   - Open Command Prompt.
   - Navigate to your project directory.
   - Execute the command:
     ```
     py -m venv venv
     ```

2. **Activate Virtual Environment:**
   - Still in Command Prompt, activate the virtual environment with:
     ```
     .\venv\Scripts\activate
     ```
   - You will see `(venv)` before your prompt, indicating the virtual environment is active.

3. **Install Dependencies:**
   - Make sure your project directory contains a `requirements.txt`.
   - Install the necessary packages by running:
     ```
     pip install -r requirements.txt
     ```

## Notes:

- Always activate the virtual environment before running your project scripts or installing new packages to ensure they are isolated from the global Python environment.
- If you encounter any issues with package versions, consider upgrading `pip` within your virtual environment using `pip install --upgrade pip`.

**Command to run the script:**
- In macOS: <code>python3 ID_Generator.py</code>
- In windows: <code>py ID_Generator.py</code>

**Sample Output**

<img width="1469" alt="image" src="C:\Users\kunig\OneDrive - Saint Louis University\Documents\SEM_2\PSD\Extra credit\ID-Card-Generator\Output.png">

