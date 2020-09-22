## Customer

### POST /users
----------
Request
```json
{
    "name": "Aravind",
    "phone": "9123456780",
    "address": [
        {
            "completeAddress": "full address",
            "landmark": "optional",
            "tag": "work/home/other"
        },
        {
            "completeAddress": "full address",
            "landmark": "optional",
            "tag": "work/home/other"
        }
    ]
}
```
Response
```json
{
    "name": "Aravind",
    "phone": "9123456780",
    "address": [
        {
            "completeAddress": "full address",
            "landmark": "optional",
            "tag": "work/home/other"
        },
        {
            "completeAddress": "full address",
            "landmark": "optional",
            "tag": "work/home/other"
        }
    ] 
}
```

### Get /users
----------------
Response 
```json
{
    "users": [
        {
            "name": "Aravind",
            "phone": "9123456780",
            "address": [
                {
                    "completeAddress": "full address",
                    "landmark": "optional",
                    "tag": "work/home/other"
                },
                {
                    "completeAddress": "full address",
                    "landmark": "optional",
                    "tag": "work/home/other"
                }
            ]
        },
        {
            "name": "Archana",
            "phone": "9123456780",
            "address": [
                {
                    "completeAddress": "full address",
                    "landmark": "optional",
                    "tag": "work/home/other"
                },
                {
                    "completeAddress": "full address",
                    "landmark": "optional",
                    "tag": "work/home/other"
                }
            ]
        }
    ]
    
}
```

### Get /users/{phone}
-----------------------
Response
```json
{
    "name": "Aravind",
    "phone": "9123456780",
    "address": [
        {
            "completeAddress": "full address",
            "landmark": "optional",
            "tag": "work/home/other"
        },
        {
            "completeAddress": "full address",
            "landmark": "optional",
            "tag": "work/home/other"
        }
    ]
}
```

### PUT /user/{phone}
------------------------
Request
```json
{
    "action": "add/delete",
    "address": [
        {
            "completeAddress": "new full address",
            "landmark": "optional",
            "tag": "work/home/other"
        }
    ]
}
```
Response
```json
{
    "name": "Aravind",
    "phone": "9123456780",
    "address": [
        {
            "completeAddress": "new full address",
            "landmark": "optional",
            "tag": "work/home/other"
        },
        
    ]
}
```

