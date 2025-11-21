InstaFlow - ManyChat-style Flow Builder (Option C)

This is a frontend-only Next.js + Tailwind + React-Flow starter for a drag-and-drop flow builder UI.

Quick start (frontend only):
1. Install dependencies:
   npm install

2. Run dev server:
   npm run dev

Notes:
- This is a UI prototype. To integrate with the backend:
  - Save flows via API (/api/flows)
  - Load saved flows and render nodes/edges
  - Connect to backend endpoints to deploy flows to Instagram automation engine

Files:
- pages/flow-builder.js : main flow editor using react-flow-renderer
- components/Sidebar.js : left navigation
- pages/dashboard.js : simple dashboard
- styles/globals.css : Tailwind styles

You can deploy this frontend on Vercel. For production, connect to backend APIs for saving/loading flows and user auth.
