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

Bugs and Features
-----------------

If you found a bug or have a feature request, please create an issue here on GitHub.

https://github.com/Crazy-Ivan/Dashboard-module-foosballProxy/issues


Author
------

**Paweł Bród**

+ https://github.com/Crazy-Ivan
+ http://www.linkedin.com/pub/pawe%C5%82-br%C3%B3d/98/4b6/37/en


License
-------

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>
