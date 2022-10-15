# [Triathlon-py](https://github.com/triathlon-py/triathlon-py/)

[Triathlon-py](https://github.com/triathlon-py/triathlon-py/) is a Python API wrapper for the [Triathlon.org](https://triathlon.org) API.

## Installation

```bash
pip install triathlon
```

## Usage

```python
from triathlon import TriathlonAPI

api = TriathlonAPI("YOUR_TOKEN")
print(api.search.athletes("james"))
```

See the [repo](https://github.com/triathlon-py/triathlon-py/) for more
