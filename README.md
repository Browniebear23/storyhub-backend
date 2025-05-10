# Storyhub Backend

This is the backend server for Storyhub — a platform where users can unlock short stories, poetry, and aesthetic videos by either paying or watching ads.

## Features

- Stripe integration for payments
- CORS-enabled Express API
- Simple POST route for creating Stripe PaymentIntent

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- A Stripe account with API keys

### Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/storyhub-backend.git
   cd storyhub-backend
   ```

2. Create a `.env` file:
   ```
   STRIPE_SECRET_KEY=sk_test_YOUR_SECRET_KEY
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Run the server:
   ```bash
   node server.js
   ```

## Deploying to Render

- Connect this repo to [Render](https://render.com)
- Set the `STRIPE_SECRET_KEY` environment variable
- Use `npm install` as the build command
- Use `node server.js` as the start command

---
Licensed under MIT
