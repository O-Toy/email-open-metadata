# email-open-metadata
A minimal, open-standard layer to make email smarter (without changing the email).
# Open Metadata Layer for Email (Proposal)

This is a throwaway idea. Feel free to take it, run with it, or ignore it completely.

## Concept

An open specification for layering metadata on top of **existing email infrastructure**, allowing enhanced UI and integration possibilities — without touching the original messages.

### Why?

Email is still the most universal communication tool, but:

- Context (e.g., project, status, response expectations) is always lost.
- Every app traps your data in a proprietary UI.
- No common metadata layer exists across providers.

We want to keep using normal mail apps (IMAP + OAuth), but **overlay context** in a structured way.

---

## Key Principles

✅ **1. IMAP + OAuth only**

- Compatible with almost any email server  
- No new backend or vendor lock-in required

✅ **2. JSON-LD for contextual metadata**

- Projects, people, priorities, replies, etc.  
- Human-readable and machine-parsable

✅ **3. UI layer stays on top, never overwrites**

- Metadata shown as an additional layer  
- Original emails remain untouched

---

## Ideal Vision

- An open standard
- Browser extension or AI assistant augments mail clients
- Optional plugins for annotation, auto-sorting, and response tracking
- Lightweight enough for personal or team use

---

## Inspiration

Somewhere between a note-taking tool, a helpdesk system, and your messy inbox.  
Let’s make email slightly less dumb — without breaking it.

---

## License

No license. No copyright. No responsibility.  
Use freely, modify recklessly.
