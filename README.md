[README.txt](https://github.com/user-attachments/files/32749984/README.txt)
IBIS Teacher Core — Vercel deployment package

Contents:
- index.html: IBIS Teacher Core v3.0.28 with Backup & Restore enhancements.

Recommended deployment route if the connected Vercel deployment action is unavailable:
1. Create a new private GitHub repository named ibis-teacher-core.
2. Upload index.html to the repository root.
3. In Vercel, choose Add New > Project and import that GitHub repository.
4. Deploy as a static site; no framework/build command is required.
5. Test the preview URL before promoting it to production.

Important: Deploying the HTML does not migrate browser-local IndexedDB data. Export a backup from the current app before switching to the hosted copy.
