# 🚀 Strapi Setup – Internship Task

This repository contains my Strapi setup completed as part of the DevOps Internship at PearlThoughts. The project was created using Strapi’s official quickstart method and includes a sample content type, initial configuration, and documentation of all steps.

## 📌 Project Overview

This project is a basic Strapi application created to:

- Understand Strapi folder structure
- Explore the Admin Panel
- Create and test content types
- Run Strapi locally
- Push the setup to a GitHub repository
- Record a Loom walkthrough of the setup

## 🛠 Tech Stack

- Strapi v5 (latest)
- Node.js (LTS recommended)
- npm
- SQLite (default Strapi quickstart database)

## 📥 1. How I Created This Project

### Step 1: Create Strapi Project

I used Strapi’s official quickstart command:

```bash
npx create-strapi-app@latest my-strapi-project --quickstart
```

- Skipped Strapi Cloud login
- Skipped anonymous A/B testing
- Automatically installed dependencies
- Launched Strapi admin panel at: http://localhost:1337/admin

### Step 2: Created Admin User

After the app started, I registered using:

- Name
- Email
- Password

This created my admin environment.

## 🗂 2. Project Folder Structure

Key directories:

```
my-strapi-project/
│
├── config/            # Application & server configuration
├── src/
│   ├── admin/         # Admin panel customizations
│   ├── api/           # Content types and routes
│   ├── components/    # Reusable components
│   └── extensions/    # Plugin extensions
│
├── .env               # Environment variables
├── package.json       # Dependencies & scripts
└── README.md          # Documentation
```

This is the standard and recommended Strapi application structure.

## 🏗 3. Created Sample Content Type

Using the Content-Type Builder, I created a new collection type:

**Collection Type:** article

**Fields added:**

| Field Name   | Type       | Notes                  |
|--------------|------------|------------------------|
| title        | Text       | Required               |
| description  | Rich Text  | Article description/body |
| published    | Boolean    | True/False             |

After creating the structure, Strapi restarted automatically.

## ✍️ 4. Added Sample Data

Using the Content Manager, I created a sample entry:

- **title:** First Article
- **description:** This is a sample content entry.
- **published:** true

This verifies the content type works.

## ▶️ 5. Running the Project

Start the Strapi project:

```bash
npm run develop
```

Admin panel opens at: http://localhost:1337/admin

## ☁️ 6. GitHub Setup

Initialize the local repository:

```bash
git init
git add .
git commit -m "Strapi setup complete with sample content type"
```

Connect to GitHub:

```bash
git remote add origin <your-github-repo-url>
git push -u origin main
```

## 🎥 7. Loom Video

A Loom video walkthrough has been recorded showing:

- Project setup
- Admin panel
- Content type creation
- Adding sample content
- Folder structure
- GitHub push

**Loom Video Link:** (Add your link here)
