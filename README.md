# Wikipedia-Article-Translation

## About the Project
This web app allows you to fetch a wikipedia article and then contribute translations in upto 8 Indian languages.

## Installation
- Option 1: Use the deployed version at: https://wikipedia-article-translation.herokuapp.com/
-----------------------------------------------------
- Option 2: 
    1. ### Setting up git:
    - [Download and install the latest version of Git.](https://git-scm.com/downloads)
    - (Optional) [Set your username in Git.](https://help.github.com/articles/setting-your-username-in-git)
    - (Optional) [Set your commit email address in Git.](https://help.github.com/articles/setting-your-commit-email-address-in-git)
    2. ### Cloning the Repo in your local machine
    - Run ``git clone https://github.com/Aneesh02/WikipediaArticleTranslation.git``
    - ``cd WikipediaArticleTranslation``
    - Make a virtual environment named .env ``python3 -m venv .env``
    - Activate ``.env`` by ``source .env/bin/activate``
    - Download the requirements ``pip install -r requirements.txt``
    - Run script ``bash setup.sh``
    - Go to  http://127.0.0.1:8000/
    - You are good to go! 🤘


## Frequently Asked Questions

**Q: I got Error: That port is already in use.**

A: It occurs because some process has occupied that port. You may kill the process using ``sudo fuser -k 8000/tcp`` or use a different port. For using a different port simply replace ``bash setup.sh`` with ``bash setup.sh <port-number>``. An example ``bash setup.sh 7000``. Now your app will successfully run on http://127.0.0.1:7000/

