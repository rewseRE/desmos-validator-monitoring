# Simple shell script for monitoring Desmos validators.
This shell script checks [Desmos](https://github.com/desmos-labs/desmos) validator node health, voting power, validator position and sent warnings to Telegram chat if the node is unsynced or something changed.
<br/>
#### Requirements
bash, curl, jq
<br/>
#### Installation
Set the variables in file monitor.sh and run script.
```bash
# Your node RPC address, e.g. "http://127.0.0.1:26657"
NODE_RPC=""
# Telegram bot API
TG_BOT=""
# Telegram chat ID
TG_ID=""
```

