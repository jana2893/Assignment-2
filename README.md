# Assignment-2
Phonepe Pulse Data Visualization Project
Phonepe Pulse Data Visualization Project
A User-Friendly Tool Using Streamlit and Plotly
Table of Contents
Overview
Problem Statement
Prerequisites
Testing the Application Locally
Features
Demo/Presentation Video
Conclusion
Contact
Overview
This project focuses on extracting, processing, and visualizing data from the Phonepe Pulse GitHub repository. The solution includes steps for data extraction, database management, and the creation of an interactive geo visualization dashboard.

Problem Statement
The Phonepe Pulse Github repository contains a large amount of data related to various metrics and statistics. The goal is to extract this data and process it to obtain insights and information that can be visualized in a user-friendly manner. The solution must include the following steps:

Extract data from the Phonepe pulse Github repository through scripting and clone it..
Transform the data into a suitable format and perform any necessary cleaning and pre-processing steps.
Insert the transformed data into a MySQL database for efficient storage and retrieval.
Create a live geo visualization dashboard using Streamlit and Plotly in Python to display the data in an interactive and visually appealing manner.
Fetch the data from the MySQL database to display in the dashboard.
Provide at least 10 different dropdown options for users to select different facts and figures to display on the dashboard. The solution must be secure, efficient, and user-friendly. The dashboard must be easily accessible and provide valuable insights and information about the data in the Phonepe pulse Github repository.
Prerequisites
Before you begin, ensure you have met the following requirements:

Python: Version 3.11.0 or higher. Download Python
IDE: Jupyter Notebook or your referred IDE's / Code editor.
MySQL Database: Ensure you have MySQL installed. MySQL Installation Guide
GitHub: Version control tool. Download Git
Streamlit and Plotly: Install using pip:
pip install streamlit plotly
Necessary Python packages: specified in requirements.txt
Features
Home Page: This page provides an overview of the PhonePe Pulse and the Streamlit app.
Datasets Page: On this page, you'll find an overview and summary of PhonePe Pulse data, and you have the option to download the data.
Overview Page: This page displays the comprehensive highlights of PhonePe Pulse Data.
Transactions Page: This page displays the transaction data using various filters such as state, year & quarter in the form of transaction hotspots and breakdowns.
User Page: This page allows users to explore the user data using various filters such as state, year and quarter treemap, choropleth and density mapbox
Trend Page: This page shows the trend of transaction count and amount over time, and allows users to compare different time periods using line and bar plots
Comparison Page: This page allows users to compare different regions, transaction types using facet grids, grouped bar and pie chart.
Testing the Application Locally:
To clone and run this application, you'll need Git Badge installed on your computer.

Clone the repository:

  git clone https://github.com/Santhosh-Analytics/Phonepe-Pulse-Data-Visualization-and-Exploration
Navigate to the project directory:

cd Phonepe-Pulse-Data-Visualization-and-Exploration
Install dependencies:

pip install -r requirements.txt
Run the application:

streamlit run Main_mod.py
Ensure you use your SQL user credentials.

Conclusion
In conclusion, this project has provided a hands-on experience in the end-to-end process of data extraction, processing, and visualization. By addressing the problem statement, we successfully developed a user-friendly geo visualization dashboard that dynamically updates with the latest data. The project has not only enhanced technical skills but also demonstrated the ability to work with databases, adhere to coding standards, and deploy a comprehensive solution.

This project serves as a valuable addition to a portfolio, showcasing practical skills in data science, database management, and dashboard development.
