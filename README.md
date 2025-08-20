# 3-Tier DevSecOps Project

This repository contains a simple Node.js API and a React client used for a user management demo. Follow the steps below to get the project running locally.

## Setup

1. Install Node.js (version 18 or later is recommended).
2. Install dependencies for both the API and client:

   ```bash
   cd api && npm install && npm install -g pm2
   cd ../client && npm install && npm install -g pm2
   
   ```

3. Start the API server:

   ```bash
   cd api
   npm start or pm2 start index.js
   pm2 list
   pm2 logs
   pm2 startup
   pm2 save
   ```

4. In a separate terminal, start the React client:

   ```bash
   cd client
   npm start
   ```

5. Open `http://localhost:3000` in your browser to use the application.

The client now displays an animated banner welcoming you to **DevOps Shack**.
