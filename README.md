# Taskara — Task Management Platform

A modern task management platform built with React, Node.js/Express, and PostgreSQL. Designed for team collaboration with real-time updates, progress tracking, and integrated features.

## Project Structure

```
Taskara/
├── backend/          # Node.js/Express API server
│   ├── src/
│   │   ├── controllers/    # Business logic (one function = one action)
│   │   ├── routes/         # API endpoints
│   │   ├── middleware/     # Auth, error handling
│   │   ├── models/         # DB queries
│   │   ├── services/       # Business logic layer
│   │   └── sockets/        # Real-time updates
│   └── tests/
│
├── frontend/         # React + Vite SPA
│   └── src/
│       ├── components/     # React components (grouped by feature)
│       ├── pages/          # Page components
│       ├── api/            # API client functions
│       ├── contexts/       # React Context state
│       ├── hooks/          # Custom React hooks
│       └── styles/         # CSS files
```

