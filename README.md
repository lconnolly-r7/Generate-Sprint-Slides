# Generate Sprint Slides Script
This is a script to generate sprint slides for the sprint demo.

## Installation
1. Clone this repository
2. Install the dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. Get your teams rapidViewId from the url of your Jira board. Example: /secure/RapidBoard.jspa?rapidView=**123**
2. Get your Jira JSESSIONID from your browser cookies.
3. Fill in the config.ini file.

```bash
python3 generate_slides.py
```