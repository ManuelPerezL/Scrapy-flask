# scrapy-poc

## How to run CAQH scrapping
Load MY_ACCOUNTS.json file with provider credentials into root dir. 
Then run:
```
scrapy crawl datasummary
```

### Run and output scrapped data to json file
```
scrapy crawl datasummary -o output.json -t json
```
### Run  and output scrapped data to json file from flask 
```
python3 app.py 
```