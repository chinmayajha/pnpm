---
"@pnpm/pnpr": minor
---

pnpr now tracks and runs numbered schema migrations for its metadata and auth tables together in the `schema_migrations` table, starting at version `1`. pnpr refuses pre-1.0 databases without `schema_migrations` at startup until you wipe their pnpr tables.
