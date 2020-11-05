# `f0cal/farm-server`

Utility methods and a CLI wrapper for the [FØCAL](https://f0cal.com) device farm
"server." The server is the piece of software, packaged here as a virtual
machine, that connects the devices on your desk to our API.

Implements the `f0cal.farm.server` Python namespace.

## Quick start

```bash
pip install f0cal.farm.server \
  -i https://dl.f0cal.com/py
  
f0cal farm --help
```
**NOTE** that many server workflows require an API key from https://app.f0cal.com.

## Installation

### `pip`

```bash
pip install f0cal.farm.server \
  -i https://dl.f0cal.com/py
```

### Source

```bash
git clone https://github.com/f0cal/farm-server && \
  cd farm-server && \
  pip install ./ -r requirements.txt -c constraints.txt
```

## More

[Official docs](https://docs.f0cal.com/farm-server)
