# Python Script to create a fast logging endpoint

## Server
``` Python
from flask import Flask

app = Flask(__name__)

@app.route('/<LogMessage>')
def Log(LogMessage):
  print(LogMessage)
  return "Success"
  
if __name__ == "__main__":
  app.run(host="IP Address")
```
Python3 script to have a console that show messages that was sent to it

## Client

``` Python
import requests
r = request.get(site/message)
```

``` Bash
curl Site/message
```

Load the webiste with message after slash
