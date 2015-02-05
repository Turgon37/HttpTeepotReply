# HttpTeepotReply - Http Teepot Reply

This projected is licensed under the terms of the MIT license

Simple http reply server which answer to a tcpconnection with a simple http code

## Usage

As a module
```python
from httpteepotreply import HttpTeepotReply

server = HttpTeepotReply(adress, port[, logger[,bind_and_activate = true]])
server.serve_forever()
```

logger if an optionnal object (from logging) that will be use to receive log

As main program
```bash
./httpteepotreply.py port
```

## Installation

Requires:
* python3
