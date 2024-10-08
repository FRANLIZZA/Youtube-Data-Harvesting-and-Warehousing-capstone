YouTube Data Harvesting and Warehousing:
This project focuses on harvesting YouTube data using Python, specifically utilizing the Google API for YouTube. The harvested data is then transformed and subsequently converted and warehoused in a MySQL server. The Streamlit framework is employed for creating an interactive web application to visualize insights derived from the harvested data.

Project Objective:
The objective of this project is to extract data from YouTube channels using the YouTube API, store the data in a transform it and then warehouse it in a MySQL server. Furthermore, the project aims to create an interactive web application using Streamlit for querying and visualizing insights from the harvested YouTube data.

Business Task:
1.Harvest data from multiple YouTube channels, including channel details, video details, and comments.
2.Transform and warehouse the data into a MySQL server for long-term storage and querying.
3.Develop an interactive web application using Streamlit to visualize insights and perform data analysis on the harvested YouTube data.

Recommendations:
1.Ensure proper authentication and quota management for accessing the YouTube API.
2.Optimize data retrieval methods to minimize API quota consumption and maximize efficiency.
3.Implement robust error handling and logging mechanisms to handle API request failures and data processing errors.
4.Regularly monitor and maintain the and MySQL databases to ensure data integrity and performance.
5.Enhance the Streamlit web application with additional features such as user authentication, caching, and data export capabilities.

Coding Process (Steps):
1.Set Up API Keys: Obtain API keys for the YouTube Data API from the Google Developer Console.
2.Data Retrieval: Harvest YouTube channel details, video details, and comments using the YouTube API.
3.Data Transformation: Transform the raw data into a suitable format for warehousing in a relational database.
4.Data Warehousing (MySQL): Create tables in a MySQL server and upload the transformed data for long-term storage.
5.Streamlit Development: Develop an interactive web application using Streamlit for querying and visualizing insights from the warehoused data.
6.Testing and Deployment: Test the application thoroughly and deploy it to a suitable hosting platform.

Getting Started:
To run the project locally, follow these steps:

1.Clone this repository to your local machine.
2.Install the required Python dependencies listed in requirements.txt.
3.Obtain API keys for the YouTube Data API.
4.Configure the API keys and database connection settings in the project files.
5.Run the Streamlit web application using the command streamlit run app.py.
6.Access the application through the provided local URL in your web browser.

Contribution:
FRAN LIZZA M
