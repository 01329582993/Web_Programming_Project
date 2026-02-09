# WebAlarm

WebAlarm is a local development project combining a Node/Express backend and a Vite/React frontend.

## Quick Start

From the project root:

```bash
cd alarm
npm install
npm run dev
```

This starts the backend on port 5000 and the frontend dev server (Vite) on 5173 (or the next available port).

## Structure (relevant folders)

- `alarm/backend` — Express server, controllers, routes, data, and uploads
- `alarm/front` — Vite + React frontend source

See `alarm/MEMBER3_README.md` for Member-specific feature notes and `DEPLOYMENT_STATUS.md` for deployment details.

## Notes

- If ports are in use, the frontend will try the next available port.
- Ensure environment variables (if used) are configured in `alarm/backend` before starting the server.

## License

MIT
