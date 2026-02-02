# Strapi Project

This is a sample Strapi project created as part of TASK-1.

## Project Overview

- Built using **Strapi v4**  
- Local development using **Node.js & npm**  
- Admin Panel for creating content types and managing content

---

## Steps Followed

1. **Installed Node.js and npm** on local machine.  
2. **Created Strapi project** using:

`bash
npx create-strapi-app my-project

3. Ran Strapi locally:
   cd my-project
   npm run develop
   Admin Panel available at http://localhost:1337/admin

4. Created Admin user

  Created Sample Content Type:

  Collection Type: Article

Fields:

  title → Text
 
  description → Rich Text

  publishedDate → Date

5. Added Sample Entry:

title	description	publishedDate
My First Article	This is a test content	2026-02-02

6. Pushed project to GitHub:

  git init
  git add .
  git commit -m "Initial Strapi project setup"
  git branch -M main
  git remote add origin https://github.com/swathisura/strapi-project.git
 git push -u origin main

## Useful Commands

Start Strapi in watch mode: npm run develop

Start Strapi without watch mode: npm run start

Build Admin Panel: npm run build

Display available commands: npm run strapi

##Links

GitHub Repository: https://github.com/swathisura/strapi-project

Admin Panel: http://localhost:1337/admin
