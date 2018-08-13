# Sweden runes

* **data.py**
```python

ramsund_runestone = "ᛋᛁᚱᚦ᛬ᚴᛁᛅᚱᚦᛁ᛬ᛒᚢᚦ᛬ᚦᚭᛋᛁ᛬ᛘᚢᚦᛁᛦ᛬ᛅᛚᚱᛁᚴᛋ᛬ᛏᚢᛏᛁᛦ᛬ᚢᚱᛘᛋ᛬ᚠᚢᚱ᛬ᛋᛅᛚᚢ᛬ᚼᛅᛚᚢ᛬ᚼᚢᛚᛘᚴᛁᚱᛋ᛬ᚠᛅᚦᚢᚱ᛬ᛋᚢᚴᚱᚢᚦᛅᚱ᛬ᛒᚢᛅᛏᛅ᛬ᛋᛁᛋ"





```
* **scraper.py** retrieves runic inscriptions from http://runes.verbix.com/index.html
  * __retrieve_sweden_runic_inscriptions__ downloads from the source all the runic inscriptions and stores them in a JSON file.
  * __read_sweden_runic_inscriptions__ reads the JSON file.
```python
retrieve_sweden_runic_inscriptions()
read_sweden_runic_inscriptions()
```
