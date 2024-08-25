https://consoleflareanalytics.streamlit.app/  (Link for the deployed app)
Consoleflare Analytics Portal
📊 Consoleflare Analytics Portal is a web-based application built using Streamlit, Pandas, and Plotly. This portal allows users to easily upload datasets, explore basic statistics, and visualize the data through interactive charts and graphs.

Features
File Upload: Supports CSV and Excel file uploads.
Data Preview: View the top and bottom rows of the dataset.
Basic Dataset Information: Provides a summary of the dataset, including the number of rows, columns, data types, and statistical summary.
Value Count: Allows counting the unique values in a selected column, with options to visualize the counts through various charts (Bar, Line, Pie).
Group By Functionality: Enables summarizing the data by specific categories with various aggregation operations (sum, max, min, mean, median, count).
Interactive Data Visualization: Choose from multiple chart types (line, bar, scatter, pie, sunburst) to visualize the grouped data.
Installation
Prerequisites
Python 3.x
Streamlit
Pandas
Plotly
Openpyxl
Installation Steps
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/consoleflare-analytics-portal.git
cd consoleflare-analytics-portal
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy code
streamlit run app.py
How to Use
Upload Your Dataset:

Click on "Drop csv or excel file" to upload your dataset.
The file will be automatically displayed in a table after successful upload.
Explore Basic Dataset Information:

View the dataset summary, top and bottom rows, data types, and column names under the "Basic Information of the Dataset" section.
Count Values:

Choose a column to count the unique values.
Adjust the number of top rows to display.
Visualize the value counts using bar, line, and pie charts.
Group By and Analyze:

Select columns to group the data by.
Choose an aggregation operation (sum, max, min, etc.).
Visualize the grouped data using various chart types like line, bar, scatter, pie, and sunburst.
Screenshots

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you find a bug or have a suggestion for improvement.


Contact
For any inquiries, feel free to reach out at your sharma.2004.04@gmail.com (Shashank Sharma)
