# Balboa ControlMySpa Whirlpool cloud API

## Usage

see example.py for runnable example

```python
from controlmyspa import ControlMySpa

API = ControlMySpa("user@example.com", "myverysecretpassword")
pprint.pprint(API._info)
```

## References

Based on the JavaScript library https://gitlab.com/VVlasy/controlmyspajs
