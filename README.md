# iQ-Live
iQ-Live trivia bot, in Python. Automatically scrapes iQ-Live Trivia questions and answers them.

## Getting Started
Requires Python 3.6+
### Dependencies
#### Required
```
aiohttp
bs4
nltk
unidecode
```
#### Optional
```
aiodns
cchardet
```
### Installation
```
git clone https://github.com/PoonamChohdhary1991/iQ-Live.git
cd iQ-Live
pip install -r requirements.txt
```
In Python 3, run:
```
import nltk
nltk.download("all")
```
Enter your bearer token and user ID in the conn_settings.txt file. These values can be found by sniffing the traffic on your phone. The bearer token should be one line, without the word Bearer.

### Usage
```
python3 hq_main.py
```
