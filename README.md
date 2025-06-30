# MERN - Product Store

Product store is one of my portfolio project. This project is to demonstrated using some technology stack like: MongoDB, Express.js, React.js and Node.js

The Product API have several endpoint:
```bash
 - POST: curl --location 'http://localhost:5000/api/products' \
--header 'Content-Type: application/json' \
--data '{
    "name": "Smart watch Xiaomi",
    "price": "49.99",
    "image":"https://unsplash.com/photos/person-holding-white-and-gold-round-analog-watch-gevGqFpwqnY"
}'

 - PUT: curl --location --request PUT 'http://localhost:5000/api/products/68624358fbb0c122f320c045' \
--header 'Content-Type: application/json' \
--data '{
    "name": "Smart watch Apple"
}'
 - DELETE: curl --location --request DELETE 'http://localhost:5000/api/products/68624358fbb0c122f320c045'

 - GET: curl --location 'http://localhost:5000/api/products'
```


## Installation
```bash
npm run install
```

## Live Demo

```
Still in progress
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
