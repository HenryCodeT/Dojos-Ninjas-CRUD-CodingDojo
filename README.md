# Dojos-Ninjas-CRUD-CodingDojo
### Python - flask - mysql
### Install packages
* ```pipenv install PyMySQL flask```
* ```pipenv shell```
* ```python server.py```

### Initial route
* ```http://127.0.0.1:5000/dojos```

### Project structure
```
├── server.py
└── dojos_ninjas_app/
    ├── __init__.py
    ├── config/
    |   └── mysqlconnection.py
    ├── controllers/
    |   └── controler_dojos_ninjas.py
    ├── models/
    |   └── model_dojo.py
    |   └── model_ninja.py
    └── templates/
        ├── index.html
        ├── dojos.html
        └── ninjas.html
  ```
  
        
