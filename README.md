# 📮 Postmaster - Smart Order Tracking System

A real-time, disguised order tracking web application built with HTML, JavaScript, and Supabase. This tool generates custom tracking links with secure admin dashboards.

### 🌐 Live Demo
[View Live Project Here](https://tracker-xi-snowy.vercel.app/)

## ✨ Features
* **Smart URL Routing:** Generates unique tracking URLs for individual targets.
* **Invisible Admin Panel:** Hidden authentication system for creators.
* **Data Capture:** Retrieves Device Battery Status, Exact GPS Coordinates, and Front Camera Snapshot.
* **Real-time Database:** Powered by Supabase for instant log updates.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript, MediaDevices API, Geolocation API
* **Backend as a Service (BaaS):** Supabase (PostgreSQL)
* **Hosting/Deployment:** Vercel / Cloudflare (Add your hosting platform here)

## 🚀 How to Set Up
1. Create a Supabase project and run the SQL commands found in `database.sql`.
2. Update the `SUPABASE_URL` and `SUPABASE_KEY` in `index.html`.
3. Deploy the `index.html` file on any static hosting platform.

## 🔒 Security Note
This project implements Supabase Row Level Security (RLS) to ensure database integrity. The application relies on the browser's native permission prompts for Camera and Location access, strictly adhering to user-consent privacy standards.
