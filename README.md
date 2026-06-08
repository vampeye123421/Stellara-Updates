# 🌌 Stellara
*A modern astronomy community & exploration platform*

![Stellara Hero](https://science.nasa.gov/wp-content/uploads/2023/06/webb-flickr-52259221868-30e1c78f0c-4k-jpg.webp)

**Observe the universe. Understand it. Share it.**

---

## ✨ What Is Stellara?

**Stellara** is a modern, science‑focused astronomy platform built for people who love space.

It brings together **real astronomical data**, a **clean and calm UI**, and **community interaction** in one place. Stellara is designed to feel like a **digital observatory**, not a social network.

Built for:
- Curious beginners
- Amateur astronomers
- Astrophotography enthusiasts
- Anyone who looks up and wants answers

---

## 🌠 Platform Overview

Stellara focuses on:
- Clarity over clutter
- Calm over noise
- Science over hype

Everything is built to let the universe speak for itself.

---

## 🔭 Current Features

### 🧭 Explore & Learn
- **NASA APOD** (Astronomy Picture of the Day) with clear explanations.
- **Astronomical events**: upcoming meteor showers, eclipses, and sky events.
- **ISS location tracker** with live map and telemetry.
- **Full Weather Analysis** optimized for astronomy/stargazing (including moon phase).

### 👥 Community
- **Community feed** with posts (text + multi‑image uploads).
- **Real‑time feed updates** (new posts appear instantly for everyone).
- **Likes and comments** on posts.
- **Edit your own posts** (content + optional image replacement).

### 🙋 Accounts & Profiles
- User accounts and profiles.
- Profile pages at `/profile/:userid`:
  - Owner‑only profile editing.
  - “My Posts” section with pagination.

### 🖼️ Gallery & Resources
- **Featured Astrophotography** gallery.
- **Glossary** and **FAQ** for quick learning.
- **Community pages** for members and contact.

### 🛡️ Core Infrastructure & Safety
- **Enterprise-Grade Rate Limiting**: Anti-brute force mechanisms implemented across public authentication, session bootstrapping, and token refresh endpoints.
- **Privacy-First Server Logging**: Built-in automated request-body sanitization to mask sensitive user data (passwords, auth tokens) before persistent logging.
- **Advanced XSS & Injection Mitigation**: Frontend rendering sanitized via a rigid HTML entity whitelist ensuring safe handling of user-generated content.
- **CORS & Environment Isolation**: Hardened Cross-Origin Resource Sharing logic configured with a strict whitelist mechanism tailored for secure production deployments.
- **Cookie Security Hardening**: Server-side authentication cookies protected via mandatory `HttpOnly`, `Secure`, and `SameSite=Strict` flag policies.
- **Dormant Transaction Layer**: Integrated Stripe infrastructure for potential premium features is completely locked and disabled in production, ensuring zero transaction risks for users.

---

## 🧭 Philosophy

- **Science first**: built on real data sources.
- **Calm by design**: minimal clutter, readable UI.
- **No gamification**: no streaks, pressure, or engagement traps.
- **Community over virality**: quality > noise.

---

## 🗺️ Release Highlights

### 🚀 v2.5.0 — June 2026
- **Complete Architecture Hardening**: Deployed robust security updates covering global session protection, advanced rate-limiting, secure server-cookie transport layers, and multi-layered client-side XSS validation.
- **Global Legal & Privacy Compliance**: Full integration of privacy policies aligned with modern international frameworks (GDPR/CCPA support). Automated session termination mechanisms for expired or recycled tokens.
- **Experimental Features Lock**: Formally deprecated or locked all incomplete premium/Stellara Pro modules and billing routes to maintain a strictly non-transactional ecosystem.

### 🚀 v2.2.x — February 4, 2026
- Real‑time community feed refresh + improved post creation UX.
- Profile pages at `/profile/:userid` + “My Posts”.
- Post editing (owner‑only).
- Improved media previews (multi‑image `+N` layout) and faster image loading.

### 🚀 v2.1.1 — January 16, 2026
- Critical authentication fixes and more stable session handling.

### 🌌 v2.0.0 — January 10, 2026
- Platform evolution: ISS tracking, expanded community, and improved tools foundation.

---

## ⚖️ Legal Status & Responsibility

Stellara is an **amateur, recreational, and hobbistic personal project** developed and maintained purely out of love for astronomy ("just for the love of the hobby").

- **No Commercial Activity & Premium Feature Lock**: Although the codebase contains experimental structures for a premium tier ('Stellara Pro' via Stripe), these features are entirely locked, non-functional, and disabled. The platform does not process payments, sell services, or conduct any commercial transactions.
- **Provided "As Is"**: The entire platform, including any locked or visible preview components, is provided strictly 'as is' without guarantees of availability, continuous development, or accuracy.
- **Limitation of Liability & Waiver of Recourse**: The creator assumes absolutely no civil or criminal liability for any direct or indirect consequences resulting from the use of this hobbyist platform. By using Stellara, you acknowledge its non-commercial state and explicitly waive any right to legal recourse, claims, or court action against the maintainer.

## 🙏 Acknowledgements

![Cosmic Divider](https://wallpapercave.com/wp/wp13572190.png)

- NASA / public astronomy data providers
- The open‑source community
- Astronomy educators and researchers

**Stellara — a shared digital observatory.** 🌌
