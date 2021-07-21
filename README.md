## karutabot

#Config

```json
  {
    "channel": "", // Channel, where will users sends commands
    "collector": 500000, // time that the collector will record
    "reactions": 2, // How many reactions must there be on the drop for the bot to snipe
    "tokens": [""], // User tokens
    "webhook": {
      "enabled": false,
      "id": "",
      "token": ""
    },
    "time": {
      "drop": {
        "delay": 1800000, // How often should the bot drop cards (30min default)
        "random": 130000 // Adds random amount of time
      },
      "wait": { // Bot will stop dropping cards for amount of time
        "enabled": true,
        "starttime": 19, // When is the bot supposed to stop doping cards
        "endtime": 0 // When is the bot supposed to start dropping cards again
      }
    }
  }
```
