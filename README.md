# Tira — Chat AI Persona

Tira is a fun, Gen-Z style chat AI with a browser frontend and Node.js backend. It enforces strict safety: no explicit sexual content, age-gate for flirty mode, and content filtering.

## Features
- **Modes**: Friendly, Sassy, Gen-Z Advice, Flirty & Romantic (PG-13), Helpful.
- **Safety**: Age-gate, blacklist filter, fallback for explicit requests.
- **Storage**: Local JSON files for chats and settings.
- **UI**: Responsive, pastel aesthetic with animations.

## Setup and Run

### Prerequisites
- **Node.js (v14+)**: Download from [nodejs.org](https://nodejs.org).
- **Browser** (e.g., Chrome).

### Installation
1. Clone or extract the project folder.
2. Navigate to the project directory.
3. Install dependencies: `npm install` (though none are required here).

### Run
1. Start the backend: `npm start` or `node tira_backend.js`.
   - Server runs on `http://localhost:8080`.
2. Open `index.html` in your browser.
3. Chat! Use the UI controls for modes, consent, etc.

### Testing
- Run sample conversations from `examples/sample_conversations.json`.
- For unit tests, use Node.js to simulate requests (see `examples/test_runner.js` if needed).

### Build (N/A for Node.js)
No compilation needed.

### Privacy Disclaimer
Tira stores chat snippets locally only. Do not share sensitive data.

### Ethics
- No explicit content allowed.
- Report issues via the UI feedback button (logs to console).

## File Structure
- `index.html`, `styles.css`, `app.js`: Frontend.
- `tira_backend.js`: Backend server.
- `data/`: Templates, blacklist, storage.
- `examples/`: Sample chats.

## Troubleshooting
- If port 8080 is busy, change it in `tira_backend.js`.
- Ensure CORS is allowed in your browser for local dev.

Enjoy chatting with Tira! ✨
