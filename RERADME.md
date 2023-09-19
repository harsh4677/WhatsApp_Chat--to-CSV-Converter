# WhatsApp Chat to CSV Converter

This Python script is designed to convert WhatsApp chat data from a text file into CSV format. It extracts various pieces of information from the chat, such as teacher and student names, session details, lesson information, and reading scores.

## Requirements

To run this script, you need:

- Python 3.x
- Required Python libraries (e.g., `csv`, `re`)

## Usage

1. Clone this repository or download the `whatsapp_chat_converter.py` file.

2. Make sure you have the necessary Python libraries installed.

3. Modify the `DATA_FILE` variable in the script to specify the path to your WhatsApp chat data text file. Update the `CSV_FILE` variable to set the name of the output CSV file.

4. Open your terminal or command prompt and navigate to the directory containing the script.

5. Run the script by executing the following command:

  Download the Script (without Git):

Simply click the "Download" button on the GitHub repository page and choose the "ZIP" option to download the script as a ZIP archive. Extract the contents to a directory of your choice.

2. Install Required Python Libraries
Before running the script, you need to ensure that you have the necessary Python libraries installed. You can do this by executing the following command in your terminal or command prompt (make sure you're in the project directory):

bash
Copy code
pip install -r requirements.txt
This command will install any required libraries specified in the requirements.txt file.

3. Configure the Script
Open the whatsapp_chat_converter.py script in a text editor of your choice and locate the configuration section at the beginning of the script. Here, you can customize the script behavior:

DATA_FILE: Specify the path to your WhatsApp chat data text file. Ensure that you provide the correct file path.

CSV_FILE: Set the name of the output CSV file. By default, it's named data.csv, but you can change it to any name you prefer.

Custom Keywords: You can also customize keywords used to identify teachers, students, session details, and more by modifying variables like TEACHER_MATCH, STUDENT_MATCH, LEVEL_MATCH, etc.

4. Run the Script
Once you have configured the script, you're ready to convert your WhatsApp chat data into a CSV file. Here's how to run the script:

Open your terminal or command prompt and navigate to the directory where you saved the whatsapp_chat_converter.py script.

Execute the following command:

bash
Copy code
python whatsapp_chat_converter.py
The script will process your WhatsApp chat data and generate a CSV file containing the extracted information.

5. Check the Output
After running the script, you can find the generated CSV file in the same directory where you placed the script. The CSV file will contain organized data, including teacher and student names, session details, lesson information, and reading scores.

Configuration
Customizing Keywords
The script allows you to customize keywords used for identifying specific information in your chat data. You can modify the following variables to match the language and structure of your chat data:

TEACHER_MATCH: Keyword for identifying teachers.
STUDENT_MATCH: Keyword for identifying students.
LEVEL_MATCH: Keyword for identifying session levels.
READING_MATCH: Keyword for identifying reading scores.
LESSON_MATCH: Keyword for identifying lesson information.
SESSION_START_MATCH: Keywords for identifying session start date information.
SESSION_MATCH: Keywords for identifying session numbers.
Debugging
To enable debugging output, set the DEBUG_LOG variable to True. Debugging output will provide additional information during script execution, which can be helpful for troubleshooting any issues.





