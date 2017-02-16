# About
This short node.js application is a simple tool to connect esp8266 websocket for debugging.
Please find [WebSocketSerialMonitor](https://github.com/tzapu/WebSocketSerialMonitor/tree/master) project for ESP8266 for more details.

This tool is an exchange for html based viewer from #tzapu.

Code is a little modified example from [websocket client example](https://github.com/theturtle32/WebSocket-Node)
## Installation

1. Clone repository
2. Install dependency

```
npm install websocket
```

# Usage

```
node log.js ws://10.1.1.0:81
```

This command would connect to websocket server on proxy esp8266 and logs from monitored esp8266 would apprear live.
