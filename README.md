
# MERN - Product Store

Product store is one of my portfolio project. This project is to demonstrated using some technology stack like:
- **MongoDB** for database management: https://www.mongodb.com/
- **Express.js** Node js framework: https://expressjs.com/
- **Vite** Tool for building the web: https://vite.dev/
- **React.js** : JavaScript framework used for front end: https://react.dev/
- **Node.js**: JavaScript runtime environment: https://nodejs.org/en
- **Chakra UI**: UI great Themes: https://chakra-ui.com/
- **Zustand** for state management: https://www.npmjs.com/package/zustand

The Product API have several endpoint:
- `POST`

```bash
 curl --location 'http://localhost:5000/api/products' \
--header 'Content-Type: application/json' \
--data '{
    "name": "Smart watch Xiaomi",
    "price": "49.99",
    "image":"https://unsplash.com/photos/person-holding-white-and-gold-round-analog-watch-gevGqFpwqnY"
}'
```

 - `PUT` 
```bash
curl --location --request PUT 'http://localhost:5000/api/products/68624358fbb0c122f320c045' \
--header 'Content-Type: application/json' \
--data '{
    "name": "Smart watch Apple"
}'
```

 - `DELETE` 
```bash
 - curl --location --request DELETE 'http://localhost:5000/api/products/68624358fbb0c122f320c045'
```

 - `GET`
```bash
 - curl --location 'http://localhost:5000/api/products'
```


## Installation
```bash
npm run install
```

## Live Demo

```
see this link to live demo: https://drive.google.com/file/d/1oI9bTp6VtR1zi0V4ES_UMBLb1TM05bQm/view
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
