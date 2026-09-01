# Security SDD

Cada endpoint privado deve verificar:
Authentication → Authorization → Validation → Business Rules → Response.

Requisitos:
- HTTPS
- CORS
- Helmet
- rate limiting
- Zod
- RLS
- tenant isolation
- secrets management
- logs sem tokens/passwords
