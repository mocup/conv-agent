# Conversational Agent Backend

## Setup
* Clone this repository: `git clone https://github.com/JieunKimHCI/convo-BE.git`.
* Install the required libraries by executing `python -m pip install -r requirements.txt`.

### MongoDB
* In order to connect to MongoDB, you will need to configure the correct environment variables.
* To do so, download the .env file pinned in Slack, and save it to the root directory. Double check that the dot is there.
* To test your connection, execute `python db/test.py`

### NLTK Data
* Run `python nltk-data-downloader.py` to download the required corpus data in your machine.

### Running Locally
* To run the program locally, run `python app.py`.
