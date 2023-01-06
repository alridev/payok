# Python payok.io API Client by zcxw
Python payok.io API Client by zcxw 
Doc: https://payok.io/cabinet/documentation/doc_main.php
## Install
```
pip install payok
```
## Example
```
from  payok import payok_api


balance = payok_api.getBalance(
    123,
    'API_KEY'
)
print(balance)
```


## License

MIT

