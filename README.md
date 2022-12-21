# augd
Automatic Upload to Google Drive


## How to set up

1. Create a google drive api for google drive and install the json file, for help go to [this](https://d35mpxyw7m7k7g.cloudfront.net/bigdata_1/Get+Authentication+for+Google+Service+API+.pdf), and name is client_secrets.json
2. Use your client_id and client_secret from the json file and place those in the settings.yaml file


## How it works

### Dic

Allows you to access the tools

python3 augd.py dic ....

#### list

Lists the files saved for upload

python3 augd.py dic list ....

#### add(--inp)

Adds a file to be saved for upload

python3 augd.py dic add --inp ....

#### rm(--inp)

Removes a file that is saved for upload

python3 augd.py dic rm --inp ....

#### upload

Uploads files that are saved

python3 augd.py dic upload ....

##### !!options with --inp take an argument!!
##### !!only works with files not folders and the files should be placed in the files directory!!


### Examples:

python3 augd.py dic add --inp example.txt

adds example.txt to the saved files


python3 augd.py dic rm --inp example.txt

removes example.txt from the saved files
