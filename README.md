# Nova Messenger — Persistent Auth Fix

This build fixes session persistence across page refreshes and keeps authentication in the SQLite-backed server session plus an HttpOnly cookie. WebSocket authentication can also use the cookie, so realtime features continue after refresh even if localStorage is unavailable.

Desktop: Enter sends a message; Shift+Enter creates a new line.

Run:

```powershell
npm install
npm start
```

Open http://localhost:3000
