# picosnitch
- See which processes make remote network connections  
- Logs and config are stored in ~/.config/picosnitch/snitch.json and updated every 10 minutes or on sigterm  
- Do not rely on this for security or anything remotely critical (only checks connections at 0.2s intervals and could miss very short lived ones, would need a network driver or event listener for better reliability)  
- Quick experiment inspired by programs such as:  
  - Little Snitch
  - OpenSnitch
  - GlassWire
  - simplewall
# run
- run as a daemon with  
`python picosnitch.py`
- or install with  
`python setup.py install`
- then run as a daemon with  
`picosnitch`
