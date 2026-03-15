# Autonoma - TikTok API Developer Demo

Welcome to the Autonoma developer landing page repository. This repository contains the static, front-facing demonstration website for Autonoma, designed specifically to outline our platform's use cases, data security practices, and compliance with the TikTok Direct Post API Developer Terms of Service.

---

## 🎯 Purpose of this Repository

This static site serves as the official landing page submitted to TikTok for API approval. It cleanly documents why Autonoma requires access to the TikTok API and proves that our application possesses the required legal and security documentation mandated by the platform.

It includes:
- **Product Overview (`index.html`)**: Details our use of OAuth 2.0 PKCE, direct post endpoints, and AES-256-GCM encryption.
- **Privacy Policy (`privacy.html`)**: Outlines data collection, third-party authentication scopes, and data retention policies.
- **Terms of Service (`terms.html`)**: Details terms of acceptable use and compliance obligations.
- **Authentication Demo (`login.html`)**: A mock enterprise authentication gateway.

## 🚀 Deployment (GitHub Pages)

This project is built using 100% vanilla HTML, CSS (via Tailwind CDN), and JavaScript, meaning no build step is required. 

To deploy this live:
1. Fork or upload this repository to your GitHub account.
2. Go to the repository **Settings**.
3. On the left sidebar, click **Pages**.
4. Under "Build and deployment", set the **Source** to `Deploy from a branch`.
5. Select the `main` branch (or whichever branch your code is on) and the `/ (root)` folder.
6. Click **Save**. 

Within a few minutes, your landing page will be entirely live and accessible via the provided GitHub Pages URL.

## 🛠 Tech Stack

- **HTML5:** Semantic architecture
- **Tailwind CSS (CDN):** Utility-first styling with custom configurations for our branding gradients (`#22d3ee`, `#a855f7`).
- **Lucide Icons:** Open-source icon set injected via unpkg.
- **Framer Motion Elements (CSS equivalents):** Entrance animations built in vanilla CSS keyframes.

## 🔒 Security Posture Note for API Reviewers

Autonoma is built with a security-first architecture. 
- We strictly adhere to TikTok's Developer Terms of Service and Data Security guidelines. 
- We never store passwords. 
- All authentication is handled securely via official OAuth 2.0 flows, and tokens are encrypted at rest. 

If you are a reviewer and have any questions regarding our architecture, please refer to the `privacy.html` policy, or contact our engineering team via the portal.
# autonoma
Official Autonoma Website
