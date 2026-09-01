# API SDD

Base: /api/v1

Groups:
- /auth
- /company
- /clients
- /services
- /quotes
- /sync
- /subscription

Public:
- GET /q/:publicToken
- POST /q/:publicToken/accept
- POST /q/:publicToken/reject

Response success:
{ "data": {} }

Response error:
{ "error": { "code": "...", "message": "..." } }
