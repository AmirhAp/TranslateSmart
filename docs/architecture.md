# Architecture

## Frontend

React + TypeScript + Vite.

Folders:
- src/pages: page-level screens
- src/components: reusable components
- src/features: domain-specific logic and UI
- src/api: API client functions
- src/types: TypeScript types

## Backend

FastAPI.

Folders:
- app/api: route handlers
- app/schemas: Pydantic schemas
- app/services: business logic
- app/repositories: data access
- app/core: settings/config

## Data flow

Frontend page
-> API client
-> FastAPI route
-> service
-> repository
-> storage/database

## Development rule

Build one vertical slice at a time.