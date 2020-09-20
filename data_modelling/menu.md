## Menu

### Post /menu
---------------
Request:
```json
{
    "name": "string",
    "price": "number",
    "category": "enum [starters, maincourse, desserts]",
    "veg": "boolean",
    "description": "optional",
    "availability": "boolean",
}
```
Response
```json
{
    "dishId": "global id",
    "name": "string",
    "price": "number",
    "category": "enum [starters, maincourse, desserts]",
    "veg": "boolean",
    "description": "optional",
    "availability": "boolean",
}
```

### Get /menu
----------
Response
```json
{
    "menu": [
        {
            "dishId": "global id",
            "name": "string",
            "price": "number",
            "category": "enum [starters, maincourse, desserts]",
            "veg": "boolean",
            "description": "optional",
            "availability": "boolean",
        }       
    ]
}
```

### Get /menu/{dishId}
------------------
Response 
```json
{
    "dishId": "global id",
    "name": "string",
    "price": "number",
    "category": "enum [starters, maincourse, desserts]",
    "veg": "boolean",
    "description": "optional",
    "availability": "boolean",
}
```

### Put /menu/{dishId}
-------------------
Request
```json
{
    "name": "string",
    "price": "number",
    "category": "enum [starters, maincourse, desserts]",
    "veg": "boolean",
    "description": "some desc",
    "availability": "boolean",
}
```
Response
```json
{
    "dishId": "global id",
    "name": "string",
    "price": "number",
    "category": "enum [starters, maincourse, desserts]",
    "veg": "boolean",
    "description": "optional",
    "availability": "boolean",
}
```

### Delete /menu/{dishId}
---------------------
No response



