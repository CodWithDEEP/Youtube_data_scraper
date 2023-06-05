YouTube Data Scraper:
  This is a Python class that allows you to scrape trending YouTube video data using Selenium and save it to a CSV file.

Dependencies:
  Python 3.x
  Selenium
  Pandas
  Installation
  Clone the repository to your local machine:

Install the required dependencies using pip:

pip install selenium pandas
Download and install the appropriate web driver for your browser. In this code example, we are using the Microsoft Edge web driver.

Usage:
  Import the YouTubeData class from the youtube_data.py file into your Python script or interactive environment.

Create an instance of the YouTubeData class by providing the YouTube URL and the path to the web driver executable.

yt_scraper = YouTubeData(url, path)
Call the all method on the yt_scraper instance to initiate the scraping process.

yt_scraper.all()
The script will launch a browser window controlled by Selenium, navigate to the provided YouTube URL, and scrape the trending video data.

After scraping the data, it will be saved to a CSV file named trending_<current-date>.csv, where <current-date> represents the current date in the format ddmmyy.

Closing the Scraper
The scraper will automatically close the browser window after scraping and saving the data. However, if you want to manually close it before completion, you can call the close method on the yt_scraper instance.

yt_scraper.close()
Please make sure to set up the appropriate web driver and modify the url and path variables according to your specific requirements.

Disclaimer:
  This code is intended for educational purposes only. Use it responsibly and respect YouTube's terms of service and data usage policies.

License
This project is licensed under the MIT License.





