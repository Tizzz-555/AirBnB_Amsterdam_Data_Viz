# AirBnB Data Filtering App

## Cleaning

I used the pandas library to read the data files and to perform some data cleaning and processing. The first five rows of each data frame are displayed, as well as some basic statistics. The code also displays information about the columns in the listings data frame.

The listings data frame is further processed to convert several columns from strings to float values, and to convert the values in some columns from strings to boolean values. Finally, the code processes the listings data frame to convert the values in several columns from strings to float values.

All of these processed data frames are saved as variables in the code for further analysis.

## App
This app is built using the Streamlit library and allows users to filter a data frame of Airbnb listings based on various criteria. The data frame is read from a CSV file, and the app displays a UI on top of the data frame that allows users to select the columns they want to filter on, and to specify the filter criteria using either a dropdown menu, a slider, or a text input field, depending on the data type of the selected column. The app also includes a checkbox that allows users to turn the filtering feature on or off.

To try out the app, visit the following [Streamlit link](https://tizzz-555-airbnb-amsterdam-data-viz-app-i2ccl0.streamlit.app/).

This app is based on this blog [here](https://blog.streamlit.io/auto-generate-a-dataframe-filtering-ui-in-streamlit-with-filter_dataframe/).
