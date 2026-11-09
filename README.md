# STREAMZONE website starter

STREAMZONE is a responsive front-end prototype for a social platform.

## Files
- `index.html` — the complete browser-based prototype.
- `README.md` — these setup notes.

## Preview
Open `index.html` in a modern browser. On a phone, transfer the file to the device and open it with a browser, or publish the folder with a static hosting provider.

## Important prototype limits
This is a front-end demonstration. Posts and likes are stored only in the current browser using localStorage. It does not yet include real accounts, a shared database, secure media uploads, real messaging, moderation tools, or production security.

## Publish with Vercel
1. Create a GitHub repository named `streamzone`.
2. Upload `index.html` and `README.md` to the repository root.
3. In Vercel, choose **Add New → Project**, import the GitHub repository, and deploy.
4. No build command is required for this static prototype. The site entry point is `index.html`.

Before launching a real social network publicly, connect a secure backend (for example, Supabase), implement authentication and database row-level security, add reporting/moderation, and test privacy and security.
