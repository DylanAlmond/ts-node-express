# ts-node-express

A boilerplate for using TypeScript with Node.js and Express. This template is preconfigured with **CORS** and **JSON** enabled.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DylanAlmond/ts-node-express.git
cd ts-node-express
```

### 2. Install Dependencies

Using npm:

```bash
npm install
```

Or with yarn:

```bash
yarn install
```

### 3. Configure Environment Variables

Use the provided `.env` file in the root directory to configure environment variables:

```plaintext
PORT=3000
```

### 4. Run the Application

#### Development Mode

To start the server in development mode with hot-reloading enabled, run:

```bash
npm run dev
```

#### Production Mode

```bash
npm run build
npm start
```

This will compile the TypeScript code into the `dist` folder, and then run it as a production-ready application.

### 5. Test the Setup

By default, the server will run on `http://localhost:3000`.