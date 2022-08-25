# auction-be

### Overview
This is a smaller part of the full project called Aution Only. Auction Only is an online system where sellers and bidders meet. The sellers publish their product for the bidder to bid. The one with the highest bidding price owns the product.

### Prerequisite
- Yarn v1.22.10 or higher.

### Installation & Development
Run these following commands in order:
```bash
1. yarn
2. yarn add global ts-node
3. yarn dev
```
(Only run step 2 if ts-node isn't installed on your machine.)

### Technology

This project is built with:
* [Knex.js](https://knexjs.org/) A batteries-included, multi-dialect (PostgreSQL, MySQL, CockroachDB, MSSQL, SQLite3, Oracle (including Oracle Wallet Authentication)) query builder for Node.js.
* [Express.js ](https://expressjs.com/) A minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
* [Socket.io](https://socket.io/) A library that enables real-time, bidirectional and event-based communication between the browser and the server.

### Environment variables

```sh
NODE_ENV="develop"
PORT="Your backend port"
DATABASE_HOST="Your database hostname"
DATABSE_PORT="Your database port"
DATABASE_USER="Your database user name"
DATABASE_PASS="Your databse password"
DATABASE_NAME="Your database name"
IC_NAME='Your cloudinary name'
IC_API_KEY='Your cloudinary API key'
IC_SECRET='You cloudinary secrect key'
IMG_FOLDER='Your cloudinary root folder' 
```
