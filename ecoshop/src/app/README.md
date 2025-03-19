# App Directory

This directory contains the main application routes and pages using Next.js App Router.

## Structure
- `(auth)/`: Authentication routes (Developer 1)
- `(dashboard)/`: Dashboard routes
  - `user/`: User dashboard (Developer 1)
  - `admin/`: Admin dashboard (Developer 2)
- `(shop)/`: Shop routes (Developer 2)
- `api/`: API routes (Developer 2)

## Ownership
- `(auth)/**`: Developer 1
- `(dashboard)/user/**`: Developer 1
- `(dashboard)/admin/**`: Developer 2
- `(shop)/**`: Developer 2
- `api/`: Developer 2

## Documentation Requirements
- Each route must include a README.md explaining its purpose
- API routes must be documented with OpenAPI/Swagger
- Protected routes must be clearly marked
- Route handlers must include error handling 