# Foosball Proxy - dashboard module
Proxy between foosball table and dashboard end users. 

## Requirements

Installed Dashboard app. 

## How to install 

1. Copy or clone or create sub module in Dashboard/modules directory 
2. Registry module in dashboard. Add this to config/default.json

```json
...
"modules/Dashboard-module-foosballProxy":{
    "tableAddress": "http://addressToFoosballTable"
},
...
```


