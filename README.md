# Cartful

### Env variables

Rename the .env.example file to .env in root folder and add the following

In root folder
```
PORT=5000
MONGO_URI=<your_mongo_db_uri>
JWT_SECRET=<your_secret>
PAYPAL_CLIENT_ID=<your_paypal_client_id>
PAYPAL_APP_SECRET=<your_paypal_secret>
PAYPAL_API_URL=https://api-m.sandbox.paypal.com
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd frontend
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

Check in browser on [http://localhost:3000/](http://localhost:3000/)


### Live url

https://cartful.onrender.com/
