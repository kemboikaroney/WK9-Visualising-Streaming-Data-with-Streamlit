# Telecom Fraud Detection Dashboard

## Introduction
This project aims to create a real-time data visualization dashboard using Streamlit to analyze streaming data from Reddit and identify fraud in the telecommunications industry. The dashboard connects to the Reddit API, collects real-time posts related to telecom fraud, processes the data, and visualizes it using Streamlit.

## Problem Statement
Fraud in telecommunications is a significant problem that costs the industry billions of dollars annually. The challenge for telecom companies is to detect and prevent fraud in real-time before it causes significant financial damage. This project aims to address this challenge by monitoring Reddit for mentions of telecom fraud and other related keywords, extracting useful information from the posts, and analyzing the data for patterns and trends related to telecom fraud.

## Project Overview
The Telecom Fraud Detection Dashboard consists of the following main components:

Data Collection: Fetches real-time posts from Reddit using the PRAW library and specified keywords.
Data Processing: Extracts relevant information from the posts and stores it in a Pandas DataFrame for further analysis.
Data Visualization: Creates an interactive dashboard using Streamlit to visualize real-time information about telecom fraud.
Deployment: Enables deployment of the dashboard to a cloud-based platform for public accessibility.
## Project Requirements
- Connect to Reddit's API and collect real-time posts related to telecom fraud and other related keywords.
- Process the posts to extract useful information, including the post text, user name, subreddit, and date/time.
- Analyze the data to identify patterns and trends related to telecom fraud and other related keywords.
- Use Streamlit to create an interactive data visualization dashboard that displays real-time information about telecom fraud and other related keywords.
- The dashboard should include at least one chart or graph that displays the data meaningfully, such as a bar chart showing the number of fraud mentions by subreddit or a line chart showing the frequency of fraud mentions over time.

## Installation
1. Clone the repository
2. Navigate to the project directory
3. Install the required Python packages

## Usage
1. Set up a Reddit Developer Account and create an app to obtain the necessary API credentials.
2. Update the `dashboard.py` file with your Reddit API credentials and adjust the keywords to monitor.
3. Run the Streamlit application locally:

4. Access the dashboard in your web browser at `http://localhost:8501`.

## Deployment
To deploy the dashboard to a cloud-based platform such as Heroku or AWS, follow these steps:
1. Create an account and set up your preferred cloud platform.
2. Install the necessary command-line tools or plugins for deployment (e.g., Heroku CLI).
3. Configure your deployment settings and environment variables as required by the cloud platform.
4. Deploy the application using the appropriate deployment command (e.g., `git push heroku main` for Heroku).

## Contributing
Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.


## Acknowledgments
- [Streamlit](https://streamlit.io) - The framework used for creating the interactive data visualization dashboard.
- [PRAW](https://praw.readthedocs.io) - The Python wrapper for the Reddit API used to collect real-time posts.
- [WordCloud](https://amueller.github.io/word_cloud) - The library used for generating the word cloud visualization.
