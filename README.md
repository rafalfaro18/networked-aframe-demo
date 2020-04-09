# networked-aframe-demo
Networked Aframe Demo

### Requirements

- Node
- NPM

### Instructions

- Run:
```sh
npm install
```

- Create an SSL certificate and put the key.pem and cert.pem files in the project folder. You can do this by running in the terminal while inside the project folder (add a passphrase when prompted if not sure what this is just type PASSPHRASE): 
```sh
openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -days 365
```

- Create a new file called simply .env with this content (substitue what's after the equals symbol for the passphrase you typed in the previous step):
```env
PASSPHRASE=PASSPHRASE
```

- Run:
```sh
npm start
```

- Navigate to:
```
http://localhost:8080
```