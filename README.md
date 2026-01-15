🛒 UMass Student Marketplace

A student-only resale marketplace built for UMass Amherst, enabling students to safely buy and sell used items such as furniture, electronics, and dorm essentials — all within the campus community.

Think OLX / Facebook Marketplace, but verified, private, and student-exclusive.

🚀 Overview

UMass Student Marketplace connects buyers and sellers using UMass email verification, ensuring trust and safety. The platform allows students to list items, browse listings, and contact sellers while the platform takes a 5% commission upon successful buyer–seller connection.

✨ Key Features

UMass-Only Authentication
Email-based sign-in restricted to @umass.edu addresses (simulation).

Marketplace Browsing
Browse items in a clean grid layout with:

Category filtering

Search functionality

Item Detail Pages

Full item descriptions

Seller verification badge

Clear commission disclosure

Contact seller flow

Post a Listing

Upload item details

Preview mode before publishing

Instant marketplace visibility

User Dashboard

View active listings

Profile summary

Listing count tracking

🧭 User Flow

Sign In

Visit the landing page (/)

Sign in using any @umass.edu email (e.g., john@umass.edu)

Browse Listings

Redirected to /browse

View items, search, and filter by category

Create a Listing

Click Sell / List Item

Fill item details

Preview before posting

Publish listing

Manage Listings

Visit /dashboard

View active listings and profile info

Contact Seller

Open an item detail page

Click Contact Seller

See contact details and fee notice

🛠️ Tech Stack

Frontend

React

Vanilla CSS (CSS variables & system-based styling)

Lucide Icons

Backend

Node.js

Express

SQLite

Architecture

REST API communication

Client–server separation

🖥️ Local Development
Prerequisites

Node.js

npm

Running the App

Start Backend

cd backend
npm install
npm start


Backend runs on:
http://localhost:3001

Start Frontend

cd frontend
npm install
npm run dev


Frontend runs on:
http://localhost:5173 (or terminal-assigned port)

🎨 Design System

Primary Color: UMass Maroon #881c1c

Style: Clean, minimal, student-friendly

UI Patterns:

Card-based layouts

Reusable buttons & inputs

Clear CTAs

Typography: Sans-serif, readability-first

🔐 Trust & Safety

Platform restricted to verified UMass emails

Seller verification badges

Clear commission transparency

No public exposure outside campus

📌 Future Enhancements

Real UMass SSO authentication

In-app messaging

Payment integration (Stripe)

Image uploads via cloud storage

Rating & review system

Mobile app version

📄 License

This project is for educational and demonstration purposes.
All rights reserved.
