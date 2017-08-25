# MQTT Relay

Subscribe to topics of one broker and publish them on another

## Setup
Use environments variables instead of arguments (easier for docker use):

| variable 	| description 	|
|:--------:	|:-----------:	|
| SOURCE    	| Complete URL of MQTT broker to subscribe to (e.g. `ws://sample.mqtt.org`)
| DESTINATION	| Complete URL of MQTT broker to publish to
| TOPICS    	| Comma-separated list of topics to relay, use `#` as wildcard. (e.g. `/foo/bar/#,/baz`)



## Start
```
npm install
npm start
``


