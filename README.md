# San Diego Glass Specialist Website

Static HTML/CSS/JavaScript site designed for standard hosting such as Hostinger.

## Publish
1. Upload the contents of this folder to `public_html`.
2. Make sure `index.html` is at the root of `public_html`.
3. Replace the generated image assets with your real project photography when available.

## Quote form
The form UI, validation, photo previews, loading state, success state, error handling, and honeypot are included. To connect the form to a Hostinger/server-side email endpoint, set `formEndpoint` in `js/config.js` to your HTTPS endpoint. Keep SMTP credentials server-side; never put them in JavaScript.

Recommended server-side SMTP configuration on Hostinger:
- SMTP host: use the SMTP host shown in your Hostinger Email account
- SMTP port: use the TLS/SSL port shown by Hostinger
- SMTP username: your Hostinger mailbox
- SMTP password: the mailbox password/app password
- From: the same authenticated mailbox
- Reply-To: the email submitted by the customer

## Content systems
- `js/portfolio.js` contains all portfolio projects.
- `js/blog.js` contains all blog posts.
- `project.html?slug=...` renders project detail pages.
- `post.html?slug=...` renders blog detail pages.

No Node.js, npm, framework, or build process is required.
