# Poker with Friends

Multiplayer Texas Hold'em — a Node/Express and Socket.IO server with a React and
TypeScript client.

> **Archived.** Built in 2020–2022 and no longer maintained. Kept for reference.

## Layout

```
server/    Express + Socket.IO server (index.js) — room state and turn broadcast
client/    React 16 + TypeScript client, MobX for table state, Reactstrap for UI
```

## Running locally

```bash
cd server && npm install && node index.js
cd ../client && npm install && npm start
```

The client expects the server on its default port; there is no deployment
configuration in the repository.

## Licence

[MIT](LICENSE)
