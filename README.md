PROOFQUEST V3

FILES
- index.html
- config.js
- schema.sql
- .nojekyll

DEMO MODE
Upload index.html, config.js and .nojekyll and the site runs immediately with browser-local data.

REAL MULTI-USER MODE
1. Create a Supabase project.
2. Open SQL Editor and run schema.sql.
3. Copy your Project URL and anon/public key.
4. Paste them into config.js.
5. Upload index.html, config.js and .nojekyll to the root of your GitHub repository.
6. GitHub Pages: Settings > Pages > Deploy from branch > main > /(root)

IMPORTANT
Use only the anon/public key in config.js.
Never put the service_role key in browser code.

This version adds:
- sign up/sign in
- shared profiles
- shared proof submissions
- shared votes
- shared leaderboard
- demo fallback
- XP and daily quest support

For a production launch, the next additions should be:
- direct image/video uploads with Supabase Storage
- reporting/moderation
- secure server-side XP claims
- spam/abuse controls
