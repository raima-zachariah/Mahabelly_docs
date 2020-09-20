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
    "description": "some desc"   
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
}
```

### Delete /menu/{dishId}
---------------------
No response



