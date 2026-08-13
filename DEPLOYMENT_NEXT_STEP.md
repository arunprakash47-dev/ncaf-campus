# Next step: make this a real multi-user live portal

V1 is intentionally standalone so it can be tested without Lovable credits or a paid service.

When you are ready for actual campus users:
1. Create/connect a Supabase project.
2. Create Auth users and matching profiles.
3. Replace localStorage with Supabase Auth/PostgreSQL/Storage.
4. Enable and test RLS so each student sees only their own complaints.
5. Add protected attachment storage.
6. Add a server-side scheduled SLA escalation function.
7. Deploy the React build to a static host.

Do not put a Supabase service-role key in the frontend.
Do not use the demo passwords in production.
