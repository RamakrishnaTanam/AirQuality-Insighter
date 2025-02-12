User Guide: Air Pollution Prediction

Introduction

The Air Pollution Prediction script retrieves real-time air quality data from the World Air Quality Index API and presents it in a graphical format. This guide provides step-by-step instructions to help you install, configure, and use the script effectively.

Step 1: Install Dependencies

Before running the script, ensure that you have Python 3 installed along with the required libraries:

Install Required Libraries

Open a terminal or command prompt and run the following command:

pip install requests matplotlib

Step 2: Obtain an API Key

To access air pollution data, you need an API key from the World Air Quality Index API.

Visit https://aqicn.org/data-platform/token/.

Create an account if you don’t have one.

Generate an API key and save it for later use.

Step 3: Download the Script

Download the Air Pollution Prediction script from the Amazing-Python-Scripts repository on GitHub.

Navigate to the repository.

Locate the Air Pollution Prediction directory.

Download the CodeAP.py file to your computer.

Step 4: Run the Script

Once you have installed the dependencies and obtained an API key, follow these steps:

Open a terminal or command prompt.

Navigate to the directory where you saved CodeAP.py.

Run the script using the command:

python CodeAP.py

Enter your city name and API key when prompted.

Step 5: View the Results

After entering the required details, the script:

Retrieves real-time air quality data for the specified city.

Displays a breakdown of pollutants such as PM2.5, PM10, NO2, SO2, O3, and Dew Point.

Generates a pie chart to visualize the air pollution levels.

This data helps you understand air pollution trends and take necessary precautions.

Example Output:

City AQI: Displays the Air Quality Index (AQI) value.

Pollutants & Concentrations: A list of individual pollutant levels.

Pie Chart: A graphical representation of the pollutants in the air.

Additional Notes

You can experiment with different cities to compare air pollution levels.

Ensure that your API key is valid and not expired.

If the script fails to retrieve data, check your internet connection and API key.

Conclusion

The Air Pollution Prediction script provides a simple way to monitor air quality in any city. By visualizing pollution data, users can make informed decisions regarding air quality and health precautions.

If you encounter any issues, consider checking the GitHub repository for updates or troubleshooting tips.

Happy Coding! 🚀

