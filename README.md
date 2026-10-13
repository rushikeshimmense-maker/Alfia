# Afia International – Official Website

**Tagline**: Global Reach. Trusted Partnerships.  
**Direct Helpline**: +91 77458 43216 (India)  
**Email**: None (as per enterprise privacy policy)  

---

## 📁 Website Structure

```
Alfia/
├── index.html              # Home Page (Hero, 4 Pillars, Showcase, FAQ, CTA)
├── about-us.html           # About Us (Story, Mission, Reliability, Pricing)
├── privacy-policy.html     # Privacy Policy (TRAI / Telecom compliant, no email)
├── terms-conditions.html   # Terms & Conditions (Messaging & Platform Terms)
├── contact-us.html         # Contact Us (Helpline + Lead Form with DND Consent)
├── 404.html                # Not Found fallback page
├── assets/
│   ├── css/
│   │   └── style.css       # Clean responsive styling & branding
│   ├── js/
│   │   └── main.js         # Mobile nav & interactive form submission
│   └── images/
│       ├── logo.jpg        # Afia International Official Logo
│       └── banner.jpg      # Afia International Global Network Banner
└── README.md
```

---

## 🌐 How to Bind Your Custom Domain on GitHub Pages

1. Go to your repository on GitHub: `https://github.com/rushikeshimmense-maker/Alfia`
2. Click **Settings** ➔ **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   * **Source**: `Deploy from a branch`
   * **Branch**: `main` (or `master`) / `/ (root)`
   * Click **Save**.
4. Under **Custom domain**:
   * Type your domain name (e.g. `afiainternational.com` or `yourdomain.com`).
   * Click **Save**.
   * Check **Enforce HTTPS**.
5. In your DNS provider (Cloudflare, GoDaddy, Hostinger, etc.), point your domain to GitHub:
   * **Apex Domain A records**:
     * `185.199.108.153`
     * `185.199.109.153`
     * `185.199.110.153`
     * `185.199.111.153`
   * **www CNAME record**:
     * `rushikeshimmense-maker.github.io`
