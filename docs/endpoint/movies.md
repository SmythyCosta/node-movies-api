

## GET http://localhost:3000/api/movies

[
    {
        "_id": "5e2a75762025a30ea428046e",
        "title": "requiem for a dream",
        "genre": {
            "_id": "5e2a73c42025a30ea428046c",
            "name": "drama"
        },
        "numberInStock": 5,
        "dailyRentalRate": 50,
        "__v": 0
    },
    {
        "_id": "5e2a75e62025a30ea4280470",
        "title": "as banquelas",
        "genre": {
            "_id": "5e2a73cc2025a30ea428046d",
            "name": "comedia"
        },
        "numberInStock": 5,
        "dailyRentalRate": 25,
        "__v": 0
    },
    {
        "_id": "5e2a76002025a30ea4280471",
        "title": "loucuras na idade média",
        "genre": {
            "_id": "5e2a73cc2025a30ea428046d",
            "name": "comedia"
        },
        "numberInStock": 5,
        "dailyRentalRate": 10,
        "__v": 0
    }
]

## GET http://localhost:3000/api/movies/id

## POST http://localhost:3000/api/movies

{
    "title": "requiem for a dream",
    "genreId": "5e2a73c42025a30ea428046c",
    "numberInStock": 5,
    "dailyRentalRate": 50
}

## PUT http://localhost:3000/api/movies/id

{
    "title": "loucuras na idade média 2",
    "genreId": "5e2a73cc2025a30ea428046d",
    "numberInStock": 5,
    "dailyRentalRate": 10
}


## DELETE http://localhost:3000/api/movies/id
