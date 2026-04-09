README
======
Personal Portfolio Project
--------------------------
This is a personal portfolio project for Thrive Club Community. 

Short instructions to deploy this static webpage (portfolio.html + portfolio.css).

Local preview
-------------
- Open `portfolio.html` in your browser.

Deploy to GitHub Pages
----------------------
1. Create a new GitHub repository and push the project:

   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main

2. In the repository Settings → Pages, set Source to the `main` branch (root) and save.
3. Your site will be available at https://<your-username>.github.io/<repo-name> shortly.


Deploy to Vercel (recommended)
-----------------------------
1. Install the Vercel CLI or go to https://vercel.com and sign in.

   npm i -g vercel

2. From the project root, run:

   vercel

3. Follow the prompts to link or create a project; Vercel will detect this is a static site and deploy.


Notes
-----
- Update files and push changes to redeploy.
