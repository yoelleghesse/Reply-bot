This script connects to Reddit using PRAW and monitors new posts and comments in a specified subreddit. It identifies posts with the word "Christmas" in the title and replies to them with a predefined message. Additionally, it scans comments within these posts for mentions of "is coming" and replies to them as well.

Install PRAW:

``pip install praw``

Create a Reddit app on the Reddit website to obtain the required credentials (client ID, client secret). 

Replace placeholders YOUR REDDIT APP ID, YOUR REDDIT APP SECRET, YOUR REDDIT USERNAME, and YOUR REDDIT ACCOUNT PASSWORD with your Reddit app ID, app secret, Reddit username, and account password, respectively. Also, update the subreddit name if needed.

Run the script:

``python reddit_christmas_commenter.py``
