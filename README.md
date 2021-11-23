# watermelondb-server

REST server to sync instances of WatermelonDB clients

## Development

```bash
# Install dependencies
yarn

# Start development server
yarn dev
```

This commands will start a server on http://localhost:3333 with hot reloading.

## Production

```bash
# Install dependencies
yarn

# Compile project
yarn build

# Go inside compiled files
cd build

# Install prod dependencies
yarn install --production

# Start server
node server.js
```
