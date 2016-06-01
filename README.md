![/u/truedota2](http://i.imgur.com/0AZujla.png)

Automated moderator bot for /r/TrueDota2.

To run, you'll need the following installed and ready to go for Python:

- PRAW (Python Reddit API Wrapper)
- YAML (AKA: pyYAML - this is used to parse config.yml)
- BeautifulSoup (to parse some web stuff)

You can simply "pip install" these packages.

IMPORTANT: you'll need to setup config.yml for this to work.

Edit config_template.yml with the appropriate username, password, and subreddit data, and then save it as "config.yml".

Once you're done, just "python run.py" and you're golden!
