
# Solar - Solana Payment Gateway📦
Supercharge your business with _Solar_. Sign up now to experience the future of payments and offer your customers the best checkout experience.

![Home Page](https://i.ibb.co/kHMtLH7/Mac-Book-Pro-14-8.png)
# Get Started

The product contains two code bases, Server abd client, the GUI which can be accessed on the website.

1. [Server](https://github.com/leostelon/payments-server)
2. [Client](https://github.com/leostelon/solar)

**Website**

[Dedocker.xyz](https://dedocker.xyz)

**CLI**
> $ npm install -g dedocker

# Technology
- **Solana** Solana is a blockchain platform which uses a proof-of-stake mechanism to provide smart contract functionality.
- **Iron Forge** Tools and services revolutionizes Solana development by providing a secure, scalable, and reliable foundation for your application.
 -  **React.js** JS library for dynamic UIs with efficient component updates. [[know more]](https://react.dev/)
 - **Node.js** JS runtime for building scalable network applications.[[know more]](https://nodejs.org/en)
 -  **Mongoose & Express.js** For API management and database.

Follow the below steps to run it locally.

## Server⚙️

1. Clone Repo.
> $ git clone https://github.com/leostelon/payments-server server
>  $ cd server
>  $ npm i
2. Add the .env file in the root directory. Add the below variables and replace them with your tokens, respectively.

	  
	  RPC_URL= < Ironforge-API-Key > [Know More](https://www.ironforge.cloud/docs/rpc-gateway/introduction)
	NODE_ENV=development
	SALT_SECRET=create-some-very-secret-secret
	MONGODB_URL=< mongodb-url > [Know More](https://www.mongodb.com/atlas/database)
	JWT_SECRET=somesecret
3. Run server!
> $ npm run start

## Client💻

1. Clone Repo.
> $ git clone https://github.com/leostelon/solar client
>  $ cd client
>  $ npm i
2. Add the .env file in the root directory. Replace the value accordingly.

		  REACT_APP_SERVER_URL=http://localhost:3000
	  
4. Run the client!
> $ npm run start

Note: It may prompt to run on a different port, hit enter.

## Todo👨‍💻
 - [x] MVP
 - [x] Private Registry
 - [ ] Temporary payment address
 - [ ] Robust analytics
