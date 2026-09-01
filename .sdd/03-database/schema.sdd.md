# Database Schema

Entidades:
- users
- companies
- clients
- services
- quotes
- quote_items
- quote_events
- sync_queue
- devices
- subscriptions

Money:
integer cents.

IDs:
UUID v4.

Tenant:
company_id em entidades de negócio.

Quotes:
DRAFT, SENT, VIEWED, ACCEPTED, REJECTED, EXPIRED, ARCHIVED.
