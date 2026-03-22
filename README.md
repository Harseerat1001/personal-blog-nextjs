# Blogging Website 🚀

A clean, modern, and fast developer blog built using **Next.js 14 App Router**, **Tailwind CSS**, and **Contentlayer**.  
This is my personal space to write about web development, programming tips, and software projects.

> Based on Timlrx's starter blog — restructured, customized, and extended for my own learning and use.

---

## 🛠️ Tech Stack

- **Next.js 14 (App Router)**
- **Tailwind CSS**
- **TypeScript**
- **Contentlayer** – MDX content management
- **Vercel** – Hosting & deployment
- **Dark Mode** – Enabled with system preference

---

## 🔧 Customizations I Made

- ✅ Switched to App Router and server components
- ✅ Fully customized color theme and fonts
- ✅ Custom layouts for blog posts
- ✅ Blog cards with animations
- ✅ Author page and project showcase
- ✅ SEO metadata per post

---

## 📁 Folder Structure
📁 app/           → Next.js App Router pages
📁 components/    → UI components like BlogCard, TOC, Layouts
📁 content/       → Blog posts in MDX
📁 data/          → Author info, site metadata, etc.
📁 public/        → Static assets
📄 tailwind.config.js
📄 contentlayer.config.ts


---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/adityawalia7/adityawalia-blog.git
cd adityawalia-blog

# Install dependencies
yarn install

# Run the development server
yarn dev

Visit http://localhost:3000 to see it live.

✍️ Writing a Blog Post
Create a new .mdx file inside content/blog/:

markdown
Copy code
---
title: "My First Blog"
date: "2025-07-09"
tags: ["nextjs", "tailwind", "personal"]
summary: "Sharing my journey of building a blog from scratch."
layout: PostLayout
---

Start writing in **Markdown** with **JSX** components!



📸 Preview
Home	Blog Post


