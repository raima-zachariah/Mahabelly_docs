## Orders

### POST /orders
-----------------
Request
```json
{
    "details": "dish1*quantity, dish2*quantity",
    "schedule": "by default now",
    "address": "add1",
	"customer_id": "phone_no",
	"status": "pending/comfirmed/rejected/delivered",
	"paymemt_method": "",
}
```
Response
```json
{
    "orderId": "orderid",
    "details": "dish1*quantity, dish2*quantity",
    "schedule": "by default now",
    "address": "add1",
	"customer_id": "phone_no",
	"status": "pending/comfirmed/rejected/delivered",
	"paymemt_method": "",
}
```

### GET /orders
----------------
Request:
filter using phone number to get the orders for a customer

Response
```json
{
    "orders": [
        {
            "orderId": "orderid",
            "details": "dish1*quantity, dish2*quantity",
            "schedule": "by default now",
            "address": "add1",
            "customer_id": "phone_no",
            "status": "pending/comfirmed/rejected/delivered",
            "paymemt_method": "",
        },
        {
            "orderId": "orderid",
            "details": "dish1*quantity, dish2*quantity",
            "schedule": "by default now",
            "address": "add1",
            "customer_id": "phone_no",
            "status": "pending/comfirmed/rejected/delivered",
            "paymemt_method": "",
        }
    ]
}
```

### GET /orders/{orderId}
--------------------------
Param: orderId

Response 
```json
{
    "orderId": "orderid",
    "details": "dish1*quantity, dish2*quantity",
    "schedule": "by default now",
    "address": "add1",
    "customer_id": "phone_no",
    "status": "pending/comfirmed/rejected/delivered",
    "paymemt_method": "",
}
```