# Crumb & Crop 🍞🌿

A hyperlocal marketplace platform connecting local bakers and fresh 
produce vendors directly with customers — cutting out the middleman 
and supporting small food businesses in local communities.

## Overview
Crumb & Crop bridges the gap between local food producers and 
consumers by providing a dedicated platform where bakers, farmers, 
and fresh produce sellers can list products and connect directly 
with nearby customers — fostering community commerce and reducing 
dependency on large retail chains.


## Features
- Vendor onboarding — bakers and produce sellers can list products
- Customer-facing marketplace for browsing local food offerings
- Direct vendor-to-customer connection
- Location-aware hyperlocal discovery
- Supabase-powered backend for real-time data and authentication


## Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 14, TypeScript, Tailwind CSS |
| Backend | Supabase (PostgreSQL, Auth, Real-time) |
| Framework | React (App Router) |
| Font | Geist via next/font |
| AI-Assisted Development | Google Antigravity, Claude |


## Project Structure
├── app/          # Next.js App Router pages and layouts
├── components/   # Reusable UI components
├── lib/supabase/ # Supabase client and database helpers
├── public/       # Static assets
└── proxy.ts      # API proxy configuration


## Database
Supabase PostgreSQL schema included:
- `supabase-schema.sql` — initial database schema
- `supabase-schema-update.sql` — schema migrations


## Getting Started
```bash
npm install
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) to view locally.


## Status
🚀 Active development — MVP in progress

---
*Full source code is private to protect the project concept. 
This repository showcases project structure and documentation only.*
