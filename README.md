Seattle Weather Dashboard
This Streamlit app displays visualizations of weather data for Seattle, Washington. The app includes a heatmap, scatter chart, and line chart that can be customized based on user preferences.

Installation
To run this app, you need to have Python 3.6 or higher installed on your computer. Clone the repository to your local machine and install the required dependencies using pip:

Copy code
pip install streamlit pandas plost altair
Usage
To launch the app, navigate to the directory where the repository is located and run the following command:

arduino
Copy code
streamlit run app.py
This will start the Streamlit server and open the app in a new browser window. You can customize the app by selecting different options in the sidebar. The app displays three rows of content:

Metrics: Displays key weather metrics for Seattle, including temperature, wind speed, and humidity.
Heatmap: Displays a heatmap of temperature data for Seattle. You can customize the color scale and aggregation method using the sidebar.
Scatter chart: Displays a scatter chart of weather data for Seattle. You can customize the x and y axes using the sidebar.
Line chart: Displays a line chart of temperature data over time for Seattle. You can customize the y axis and plot height using the sidebar.
Data
The weather data used in this app is sourced from the seattle-weather.csv file, which is included in the repository. The file contains weather data for Seattle, Washington from 1948 to 2017. The data is parsed using the pandas library and displayed using the plost and altair libraries.

Credits
This app was created by Sucharitha Reddy Tiyyagura.





