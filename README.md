# flask-sqlalchemy-rest-api

tried to learn how to implement a simple restful api which does all the crud operations with sqlite db.

### Import these

```python
from math import prod
from flask import Flask, request, jsonify
from flask_sqlalchemy import SQLAlchemy
from flask_marshmallow import Marshmallow
import os
```
### Run these lines

```bash
# Create DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhst:5000)
python app.py
```

### Endpoints

* GET     /product
* GET     /product/:id
* POST    /product
* PUT     /product/:id
* DELETE  /product/:id

### Test with Postman
![POST](img/스크린샷(3).png)
![POST](img/스크린샷(4).png)
![POST](img/스크린샷(5).png)
![POST](img/스크린샷(6).png)
![POST](img/스크린샷(7).png)
![POST](img/스크린샷(8).png)
![POST](img/스크린샷(9).png)
### Followed a tutorial by Traversy Media
[REST API With Flask & SQL Alchemy](https://www.youtube.com/watch?v=PTZiDnuC86g)