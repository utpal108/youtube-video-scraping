

# Web Scraping YouTube Video Comments

## Overview

The project aims to gather data from YouTube video comments using web scraping techniques. YouTube, being one of the largest video-sharing platforms, hosts a vast amount of user-generated content, including comments. Extracting and analyzing these comments can provide valuable insights into audience sentiments, preferences, and engagement patterns.

## Features

- **Scalability**: Easily scale the scraping process to collect comments from YouTube videos.
- **Easy to use**: Paste your YouTube video URL and extract the comments of this video.

## Getting Started

### Prerequisites

- Python 3.x
- BeautifulSoup4


### Steps to run

<div style="padding-bottom:10px"><b>STEP 00 :</b> Clone the repository</div>

```bash
git clone https://github.com/utpalpaul108/review-scrapper-aws.git
```
<div style="padding-top:10px"><b>STEP 01 :</b> Create a virtial environment after opening the repository</div>

Using Anaconda Virtual Environments

```bash
conda create -n venv python=3.10 -y
conda activate venv
```
Or for Linux operating system, you can use that

```bash
python3.10 -m venv venv
source venv/bin/activate
```

<div style="padding-top:10px; padding-bottom:10px"><b>STEP 02 :</b> Install the requirements</div>

```bash
pip install -r requirements.txt
```

Finally, run the following command to open your application:
```bash
python app.py
```

<div style="padding-top:10px"><b>STEP 03 :</b> Open the application</div>

Now, open up your local host with a port like that on your web browser.
```bash
http://localhost:8080
```

After opening the application, you will find a search box. Here, you have to paste the Youtube video URL and extract the comments of the video in a csv file.
