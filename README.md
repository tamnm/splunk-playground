[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/tamnm/splunk-playground)

1. Pull image `docker pull splunk/splunk:latest`
2. Run splunk `$ docker run -d -p 8000:8000 -e "SPLUNK_START_ARGS=--accept-license" -e "SPLUNK_PASSWORD=<password>" --name splunk splunk/splunk:latest`
3. Specify a custom SPLUNK_PASSWORD - be sure to replace <password> with any string that conforms to the Splunk Enterprise password requirements. 
