# Movazigroup — Web Platform & LMS

**Multi-brand web platform for an architecture and design studio in Madrid.**  
Three sub-brands — Movazi Architects, Movazi Visual, Movazi Academy — under one visual identity.

🌐 [movazigroup.com](https://movazigroup.com)

---

## What was built

### Multi-page Marketing Website
Six interconnected pages (Home, About, Services, Contact, Architects, Visual) in pure HTML/CSS.  
Animated hero sections · scroll-triggered effects · ecosystem dropdown nav · portfolio galleries · fully responsive mobile layout.

### Movazi Academy — Full LMS

**Public**
- Course catalog with language filters (EN/ES), discount badges, recording status indicators
- Two enrollment flows: Stripe card payment and manual access code entry

**Student Portal**
- Dashboard with course progress tracking
- Lesson viewer with YouTube embed
- Messaging system · Certificate download

**Admin Panel**
- Course management (create, edit, delete)
- Lesson management · Student overview
- Message inbox with reply · Access code generation

**Certificate System**
- Generated client-side via Canvas API
- Issued automatically when student reaches 100% completion
- Downloadable as PNG with custom stamp and branding

---

## Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML / CSS / JS |
| Backend | Supabase — PostgreSQL · Auth · Storage · Edge Functions |
| Payments | Stripe API (via Edge Functions — server-side) |
| Notifications | Telegram Bot API |
| Certificates | Canvas API |
| Auth | JWT — role separation (admin / student) |

---

## Scale

```
10+   HTML pages deployed
15+   Database tables with RLS policies
3     Supabase Edge Functions
2     Payment / enrollment flows
1     Certificate system with custom branding
```

---

*Built by [sinadsml](https://sinadsml.xyz) · [info@sinadsml.xyz](mailto:info@sinadsml.xyz)*
