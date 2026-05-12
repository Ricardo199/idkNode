# node-react-sandbox

Minimal Node.js + Express sandbox that serves static HTML pages demonstrating basic React usage.

## Requirements

- [Node.js](https://nodejs.org/) 18+

## Run

```bash
npm install
npm start
```

Server default: `http://localhost:3000`  
Set `PORT` to override.

## Development

```bash
npm run dev
```

## Routes

| Route | Purpose |
|---|---|
| `/` | Basic React hello-world page (`public/index.html`) |
| `/recipe` | Baked salmon recipe example (`public/recipe.html`) |

## Structure

```text
public/
  index.html
  recipe.html
src/
  server.js
package.json
README.md
```

## Notes

- No lint/build/test scripts are currently defined in `package.json`.
- License in `package.json`: MIT.
