# ADR-001: FitFlow Technology Architecture

## Status
Accepted

## Context
FitFlow requires cross-platform mobile and web support,
AI-powered workout recommendations, real-time social features,
nutrition tracking, high performance, security, and scalability.

## Decision
The selected technology stack is:

- React Native for mobile
- React for web
- Node.js / NestJS for the main backend
- Python / FastAPI for AI services
- PostgreSQL for structured data
- Firebase / Firestore for real-time features
- Firebase Authentication for authentication
- TensorFlow Lite for AI/ML features

## Consequences
This architecture provides good cross-platform development,
real-time capabilities, AI integration, scalability, and
maintainability.

The hybrid architecture introduces additional service management
complexity, so clear service boundaries and security controls
are required.
