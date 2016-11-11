# directory-constants

## Requirements

```shell
pip install -r requirements.txt
```

## Installation

```shell
pip install -e git+https://git@github.com/uktrade/directory-constants.git@0.0.1#egg=directory-constants
```

## Usage

```python
# urls.py
from directory_constants import urls as external_urls

url_patterns = urls.url_patterns + [
   ...
]
```

## Development

    $ git clone https://github.com/uktrade/directory-constants
    $ cd directory-constants

## Testing
	$ make test
