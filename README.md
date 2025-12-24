🔍 FINDIT — Smart Lost & Found System

A calm, privacy-aware web application designed to help people report, discover, and recover lost items with clarity and trust.


🧩 The Problem We Noticed

On campuses and shared spaces, losing a personal item often leads to:

panic and confusion,

scattered WhatsApp messages,

physical notice boards that go unnoticed,

and no clear verification when an item is finally returned.

Most systems focus only on reporting items — not on closing the loop once the item is recovered.


💡 Our Approach

FINDIT was built with one simple goal:

Reduce stress around lost items by making the process transparent, verified, and human-centered.

Instead of overloading users with features, we focused on:

a clean reporting flow,

clear visibility of items,

and a reliable confirmation mechanism when an item is successfully returned.


⚙️ How FINDIT Works

Report Lost Item
Users submit details of a lost item (name, location, date, contact info, optional image).

Report Found Item
Users who find an item submit matching details.

Smart Matching
The system checks for matching lost–found entries based on item name and location.

Email-Based Confirmation
If a match is found, an email is sent to the person who lost the item with a confirmation link.

Resolution & History
After confirmation, the item is removed from active listings and safely stored in history.

This ensures the system doesn’t just list items — it confirms recovery.


🖌 Design Philosophy

FINDIT intentionally uses:

Minimal UI to reduce cognitive load

Forest green & beige tones to evoke calm and trust

Simple forms that work well on both desktop and mobile

Every design decision was made to keep the user experience stress-free.


🔒 Privacy & Safety Considerations

We deliberately avoided unnecessary backend features that could:

collect sensitive data without clear ownership,

require personal email/phone handling during a hackathon,

or introduce security risks close to submission deadlines.

For this reason:

The Contact Us page is currently frontend-only.

No personal admin email or phone number is hardcoded.

All critical flows are limited to essential functionality only.

This was a conscious engineering decision, not a limitation.


🛠 Technology Stack

Frontend: HTML, CSS, JavaScript

Backend & Database: Firebase Firestore

Authentication Logic: Email-based confirmation flow

Hosting: GitHub Pages

Google Technology Used: Firebase (Google Cloud)


🚀 Future Enhancements

Planned improvements beyond the hackathon scope include:

Backend integration for Contact Us queries

Admin dashboard for moderation

Role-based access (student / guard / staff)

AI-assisted matching for partial item details

Campus-wide deployment support

QR-based tagging for found items


🤝 Team Notes

This project was built with a focus on:

stability over feature overload,

clarity over complexity,

and real-world usability over assumptions.

FINDIT is designed to be ready today, while remaining scalable for tomorrow.
