# China Hotfix

Instead of making external call to get public IP, the IP must be hardcoded.

## Affect files:

* clientPostIP.py - just IP because port is added programatically
* solarProtocol.py - ip + port
* create_html.py - 2x ip + port
* viz.py - ip + port


## Git 

`git pull https://github.com.cnpmjs.org/alexnathanson/solar-protocol/ china-hotfix`