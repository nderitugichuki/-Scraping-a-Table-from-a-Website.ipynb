# -Scraping-a-Table-from-a-Website.ipynb
**Web Scraping Project: Extracting Data from Wikipedia's List of World's Biggest Public Companies**

**Overview:**
This project involves scraping data from Wikipedia's page listing the world's biggest public companies. The data includes various attributes such as company name, industry, market capitalization, revenue, and others. We'll be utilizing Python along with libraries like Beautiful Soup and requests to scrape and parse the data from the webpage.

**Project Structure:**
1. **`main.py`**: This is the main Python script where the web scraping process is initiated.
2. **`requirements.txt`**: This file lists all the dependencies required for the project.
3. **`README.md`**: This document provides instructions and information about the project.

**Dependencies:**
Ensure you have the following Python libraries installed. You can install them using pip with the command `pip install -r requirements.txt`.
- `beautifulsoup4`: For parsing HTML content.
- `requests`: For making HTTP requests.

**How to Run:**
1. Clone the repository to your local machine.
   ```
   git clone <repository_url>
   ```
2. Navigate to the project directory.
   ```
   cd <project_directory>
   ```
3. Install the required dependencies.
   ```
   pip install -r requirements.txt
   ```
4. Run the main Python script.
   ```
   python main.py
   ```

**Output:**
The script will scrape data from Wikipedia's page listing the world's biggest public companies and store it in a structured format. By default, the output will be saved in a CSV file named `companies_data.csv`.

**Notes:**
- Wikipedia's layout might change over time, so ensure that the HTML structure of the page remains consistent with the parsing logic.
- This script is meant for educational and informational purposes only. Be mindful of Wikipedia's terms of use and considerate of their servers when scraping data.

**Contributing:**
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request on GitHub.
