# YouTube Channel Video Scraper

**YouTube Channel Video Scraper** is a web application that allows users to scrape video data from any YouTube channel. This application uses Selenium for browser automation to gather and display information such as video titles, links, views, and upload times.

## Features

- **Dynamic Channel Search**: Input a YouTube channel handle to fetch videos from that channel.
- **Detailed Video Information**: Retrieve and display video titles, links, views, and upload times.
- **Headless Browser**: Operates in headless mode for efficiency and background processing.

## Prerequisites

1. **Python 3.x**: This project requires Python 3.x. If you do not have Python installed, please download and install it from [python.org](https://www.python.org/downloads/).

2. **Web Browser Driver**: You will need a compatible web browser driver for Selenium. For example, ChromeDriver for Google Chrome.

   - **ChromeDriver**: Download from [ChromeDriver](https://sites.google.com/chromium.org/driver/) and ensure it is in your system's PATH.

## Installation and Setup

### Clone the Repository

If you have a GitHub account and Git installed, you can clone the repository using the following command:

```bash
git clone https://github.com/vcdhruv/Youtube-Scraper.git
cd your-repository

If you do not have a GitHub account or prefer not to use Git, you can download the project as a ZIP file:

Visit the repository page on GitHub.
Click the "Code" button.
Choose "Download ZIP" and extract the contents to your local machine.
Set Up the Environment
Install Python: Verify Python 3.x installation by running python --version or python3 --version in your terminal.

Create a Virtual Environment:

bash
Copy code
python -m venv env
Activate the Virtual Environment:

On Windows:

bash
Copy code
env\Scripts\activate
On macOS/Linux:

bash
Copy code
source env/bin/activate
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Install Web Browser Driver: Ensure you have the appropriate driver installed (e.g., ChromeDriver) and that it is available in your system's PATH.

Running the Application
Start the Flask Application:

bash
Copy code
python app.py
Access the Web Interface: Open a web browser and navigate to http://127.0.0.1:5000/ to use the application.

Usage
On the homepage, enter a YouTube channel handle (e.g., PW-Foundation) into the search box and click "Submit."
The application will fetch and display a list of videos from the specified channel, including titles, video links, view counts, and upload times.
Troubleshooting
No Data Returned: If no data is returned or an error occurs, verify that the channel handle is correct and that the channel has public videos.
Python Not Installed: If Python is not installed, download and install it from python.org. Follow the installation instructions for your operating system.
Missing Dependencies: If you encounter issues with missing modules, ensure you have activated the virtual environment and installed all dependencies using pip install -r requirements.txt.
Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!
