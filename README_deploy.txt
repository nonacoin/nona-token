NONA static site (landing page) with Netlify CMS support - quick deploy (free)

What this package contains:
- index.html : landing page (Persian/Farsi)
- styles.css  : styles
- logo.svg    : placeholder logo
- admin/index.html : Netlify CMS admin entry page
- admin/config.yml : Netlify CMS configuration
- README_deploy.txt : step-by-step deploy instructions

Quick deploy to Netlify (free):
1. Create a new GitHub repository and push these files to the repository root.
2. Go to https://app.netlify.com/new and connect your GitHub repo (choose the repo you created).
3. In Netlify dashboard - Site settings -> Identity -> Enable Identity service.
4. In Identity -> Services -> Git Gateway -> Enable Git Gateway.
5. In Identity -> Invite users (or enable registration) to allow editing.
6. Open https://your-site.netlify.app/admin to access Netlify CMS.
7. For edit permissions, configure and invite your GitHub account via Identity.

Notes:
- Netlify free tier provides hosting and SSL (https) at no cost.
- If you prefer GitHub Pages instead of Netlify, you can host the static files on GitHub Pages but Netlify CMS requires Netlify Identity/Git Gateway to edit the content directly through the CMS.
- I can help set up the GitHub repo and Netlify connection step-by-step if you want.

If you want, I can also:
- Customize the content and images
- Create social links and token contract address insertion
- Deploy the repo to Netlify and send you the live URL (you will need to authorize Netlify with your GitHub account)
