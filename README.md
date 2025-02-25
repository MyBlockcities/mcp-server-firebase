# Firebase MCP Server

This is a Model Context Protocol server for Firebase that provides a unified interface to interact with Firebase services including Authentication, Firestore, and Storage.

## Setup

1. Clone and build the project:
```bash
git clone https://github.com/gemini-dk/mcp-server-firebase
cd mcp-server-firebase
npm install
npm run build
```

2. Configure service account key - you need to provide a Firebase service account key file.

3. Configure your MCP settings file with the path to the service account key.

## Available APIs

- Authentication
  - Get user by ID or email
- Firestore
  - Add/update/delete documents
  - List collections/documents
- Storage
  - List files
  - Get file info
