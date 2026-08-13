# NCAF Campus Management System — Phase 1

A clean standalone React/Vite portal for the NCAF Complaints & Grievance module.

## Current phase
- Official NCAF logo included.
- Government of India / Ministry of Communications institutional interface.
- Student, Supervisor, Admin and Super User roles.
- Unlimited student username convention: student1, student2, ... studentN.
- Mobile number optional.
- Normal SLA: 24 hours.
- Emergency SLA: 2 hours.
- Supervisor -> Admin escalation.
- Admin -> next escalation after 24 hours.
- Super User priority control.
- Other modules are Coming Soon.
- Zero legacy/test/sample complaints.

## Development
1. Install Node.js LTS.
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the localhost address shown by Vite.

## Demo login
student1 / student1
student2 / student2
supervisor / supervisor
admin / admin
superuser / superuser

## Important
This V1 is deliberately dependency-light and runs locally with browser storage so it can be tested without Lovable credits or a paid backend.

For a real multi-user live deployment, the next step is to replace localStorage authentication/data with Supabase Auth + PostgreSQL + RLS + Storage and move automatic SLA escalation to a server-side scheduled function. Do not use the demo credentials in a public production deployment.


## V2 additions
- Admin MIS dashboard with all complaint statuses.
- Category-wise complaint report.
- Supervisor performance metrics: handled, resolved, SLA breaches, escalations, average resolution time and resolution rate.
- Complaint status register.
