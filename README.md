# airledger.co.uk marketing site

Static site (HTML, CSS, a little JS, no build step). Will move to its own repository
(`airledger/airledger-website`) and deploy to GitHub Pages on airledger.co.uk.

The waiting list form calls `join_waitlist()` on the live Supabase project; the SQL is in
`waitlist.sql` (also a migration in the app repo). Read sign-ups in the Supabase
dashboard, Table Editor, `waitlist`.
