## Generate a Self Signed Certificate

```
openssl req -x509 -newkey rsa:4096 -nodes -keyout key.pem -out cert.pem -days 365
```
runned from terminal

## Using Helmet.js

### Installation
```
npm install helmet
```
