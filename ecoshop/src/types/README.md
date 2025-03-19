# Types Directory

This directory contains TypeScript type definitions and interfaces used throughout the application.

## Structure
- `interfaces/`: Component and feature interfaces
- `api/`: API request/response types
- `models/`: Data model types

## Ownership
- `interfaces/`: Shared between both developers (changes require notification)
- `api/`: Developer 2 (API owner)
- `models/`: Shared between both developers (changes require notification)

## Documentation Requirements
- All interfaces must be documented with JSDoc comments
- Breaking changes to shared interfaces require prior agreement
- API types must be versioned and documented 