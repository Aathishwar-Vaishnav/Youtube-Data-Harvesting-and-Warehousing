# Youtube-Data-Harvesting-and-Warehousing
Introduction
YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.


Table of Contents
1.	Key Technologies and Skills
2.	Installation
3.	Usage
4.	Features

Key Technologies and Skills
•	Python
•	SQL
•	Pandas
•	Application Programming Interface (API)
•	Streamlit

Installation
To run this project, you need to install the following packages:
pip install google-api-python-client
pip install pandas
pip install mysql-connector-python
pip install streamlit


Usage
To use this project, follow these steps:
1.	Clone the repository: git clone (https://github.com/Aathishwar-Vaishnav/Youtube-Data-Harvesting-and-Warehousing)
2.	Install the required packages: pip install packages
3.	Run the Streamlit app: streamlit run YDHWF.py
4.	Access the app in your browser


Features
Data Collection: Utilize the Google API to retrieve comprehensive data from YouTube channels. The data includes information on channels, playlists, videos, and comments. By interacting with the Google API, we collect the data and merge it into a JSON file..
Migrating Data to SQL: The application allows users to migrate data from extracted data to a SQL data warehouse. Users can choose which channel's data to migrate. To ensure compatibility with a structured format, the data is cleansed using the powerful pandas library. Following data cleaning, the information is segregated into separate tables, including channels, playlists, videos, and comments, utilizing SQL queries.
Data Analysis and Visualization: The project provides comprehensive data analysis capabilities using Streamlit. With the integrated library, users can create interactive and visually appealing insights from the collected data.
•	Channel Analysis: Channel analysis includes insights on playlists, videos, subscribers, views, likes, comments, and durations. Gain a deep understanding of the channel's performance and audience engagement through detailed visualizations and summaries.
•	Video Analysis: Video analysis focuses on views, likes, comments, and durations, enabling both an overall channel and specific channel perspectives. Leverage visual representations and metrics to extract valuable insights from individual videos.
The Streamlit app provides an intuitive interface to interact with the charts and explore the data visually.
Users can customize the visualizations, filter data, and zoom in or out to focus on specific aspects of the analysis. With the capabilities of Streamlit, the Data Analysis section empowers users to uncover valuable insights and make data-driven decisions.


Contact
📧 Email: aathi54208@gmail.com
🌐 LinkedIn: www.linkedin.com/in/aathishwar-vaishnav
