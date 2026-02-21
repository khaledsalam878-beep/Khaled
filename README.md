# EduCenter SaaS Prototype

A single-page SaaS Educational Center Management System that includes:

- Multi-tenant teacher accounts with separate dashboards and isolated data.
- 7-day free trial for every teacher account.
- Monthly subscription renewal flow.
- Automatic account lock when trial and paid subscription expire.
- Students management with per-student QR generation.
- QR attendance scanning and attendance log.
- Student payments tracking and reporting KPIs.
- Platform admin panel to monitor teachers and lock/unlock accounts.
- Security/scalability-oriented design notes in the app architecture:
  - Tenant isolation by teacher account id.
  - Basic credential hashing for demo purposes.
  - Role-based sessions (`teacher` / `admin`).

## Run locally

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Admin credentials

- Email: `admin@educenter.app`
- Password: `Admin#123`
