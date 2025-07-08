# Unit 7 Code Along: Inventory Database

A inventory database to learn how to use Express.js and SQLite.

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Create database and tables:
   ```bash
   node database/setup.js
   ```

3. Seed database with sample data:
   ```bash
   node database/seed.js
   ```

4. Start the server:
   ```bash
   npm start
   ```

## API Endpoints

- `GET /api/products` - Get all product
- `GET /api/products/:id` - Get product by ID
- `POST /api/products` - Create new product
- `PUT /api/products/:id` - Update product
- `DELETE /api/products/:id` - Delete product

## File Structure

```
server.js
database/
├── setup.js
├── seed.js
└── inventory.db
package.json
README.md
```