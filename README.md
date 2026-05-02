# node-react-sandbox

A minimal Node.js + Express server for experimenting with React concepts using `React.createElement`.

## Prerequisites

- [Node.js](https://nodejs.org/) v18 or later

## Getting Started

```bash
# Install dependencies
npm install

# Start the server
npm start
```

The server listens on **http://localhost:3000** by default.  
Set the `PORT` environment variable to use a different port.

### Development (auto-restart on file changes)

```bash
npm run dev
```

## Pages

| Route | Description |
|-------|-------------|
| `/` | React hello-world — renders an `<h1>` via `React.createElement` |
| `/recipe` | Baked Salmon recipe page with `React.createElement` example |

## Project Structure

```
.
├── public/          # Static files served by Express
│   ├── index.html   # React hello-world example
│   └── recipe.html  # Baked Salmon recipe example
├── src/
│   └── server.js    # Express entry point
├── package.json
└── README.md
```

## License

[MIT](LICENSE)
