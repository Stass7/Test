# Stripe Checkout Server

This repository contains a minimal example of a Stripe Checkout server implemented with Node.js and Express.

The server lives in the `stripe-checkout-server` directory.

## Setup

1. Install dependencies (requires internet access):

   ```bash
   cd stripe-checkout-server
   npm install
   ```

2. Set your Stripe secret key in the environment:

   ```bash
   export STRIPE_SECRET_KEY=your-key-here
   ```

3. Start the server:

   ```bash
   npm start
   ```

The server exposes a `POST /create-checkout-session` endpoint that returns a Checkout Session ID.
