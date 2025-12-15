
# 🚀 HRS Design: W3.CSS Implementation (Black, White, Yellow Theme)

This repository contains the complete, one-page static website for the HRS Design freelance business. This version is built using the **W3.CSS framework** for a robust, mobile-responsive layout and features a high-impact **Black, White, and Yellow (#FFD833) color scheme** to ensure brand distinctiveness.

## 💡 Competitive Strategy Summary

The core goal of this website is to position HRS Design as the **expert-level, efficient alternative** to traditional agencies, directly addressing client pain points (high cost, junior staff).

| Competitive Strategy | Implementation Details |
| :--- | :--- |
| **Theme & Branding** | Uses the energetic Yellow (`#FFD833`) against Black/White for a modern, memorable look. |
| **Expert Positioning** | **H1:** "Outrank the Agencies. Get Digital Strategy from the Expert." |
| **Mobile-First SEO** | Utilizes W3.CSS responsiveness and specific CSS overrides to guarantee clean flow on mobile devices. |
| **Asset Leverage** | Includes dedicated section (`#assets`) for cross-promotion with the **10K Motivation IG** and the **Job Posting Network**. |
| **Service Focus** | Portfolio emphasizes **measurable results** (e.g., "45% increase in site speed"), not generic project photos. |

## 🛠️ Project Structure and Setup

This is a single-file project, relying on external CDNs for the framework and fonts.

### 1. File Structure

This project uses a single HTML file:


hrsdesign-website/
└── index.html     <-- The complete website (HTML, CSS variables, JS)

**Note:** The styling is handled *internally* via the `<style>` tag and external W3.CSS links. No separate `style.css` file is needed for this version.

### 2. Required External Resources (CDNs)

The website relies on the following CDN links found in the `<head>` section:
* `https://www.w3schools.com/w3css/5/w3.css` (W3.CSS Framework)
* `https://fonts.googleapis.com/css?family=Montserrat` (Font)
* `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css` (Icons)

### 3. Deployment

Simply upload the `index.html` file to your web host's root directory (e.g., `public_html`).

## 🔗 Critical Links to Update

Before going live, **you must replace the placeholder URLs** in `index.html`:

| Placeholder Link | Location in `index.html` | Action |
| :--- | :--- | :--- |
| `mailto:your@email.com` | `#contact` section | **Replace with your professional email address.** |
| `[Link to Case Study]` | `#portfolio` section (3 instances) | **Replace with links to your live client work or case study pages.** |
| Social Media Icons | `<footer>` section | **Update all four social links** to your actual profile URLs. |
| **Job Posting & Instagram Assets** | Links for these must be manually added to the `#assets` section content. |

## 📐 Key Sections Mapping (W3.CSS)

The one-page structure maps the content as follows:

| Navigation Link | Section ID | HRS Design Content |
| :--- | :--- | :--- |
| **STRATEGY** | `#home` | Hero Section (H1, Value Proposition) |
| **ADVANTAGE** | `#about` | My Unique Advantage & Detailed Services |
| **PORTFOLIO** | `#portfolio` | Selected Projects & Case Studies |
| **CONTACT** | `#contact` | Contact Form and Availability |

---



