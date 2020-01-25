

## GET http://localhost:3000/api/customers

[
    {
        "isGold": true,
        "_id": "5e2a79352025a30ea428047c",
        "name": "A Smythy C Costa",
        "phone": "xx xxxx-xxxx",
        "__v": 0
    },
    {
        "isGold": true,
        "_id": "5e2a799a2025a30ea428047d",
        "name": "R Russo",
        "phone": "xx xxxx-xxxx",
        "__v": 0
    }
]

## GET http://localhost:3000/api/customers/id

## POST http://localhost:3000/api/customers

{
    "name": "A Smythy C Costa",
    "isGold": true,
    "phone": "xx xxxx-xxxx"
}

## PUT http://localhost:3000/api/customers/id

{
    "name": "A Smythy C Costa",
    "isGold": true,
    "phone": "xx xxxx-xxxx"
}


## DELETE http://localhost:3000/api/customers/id
