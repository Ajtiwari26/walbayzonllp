# Walbayzon Shopify Landing Page & Sections

This folder contains a complete suite of Shopify Liquid sections built to copy the exact layout, copy, styling, and premium aesthetics of `walbayzon.netlify.app`. 

All sections are fully integrated with the **Shopify Theme Editor**, allowing you to customize headlines, links, colors, lists, menus, and visual settings without editing code.

---

## 📂 File Structure

- **`sections/walbayzon-announcement.liquid`**: Configurable announcement bar with sticky top behavior.
- **`sections/walbayzon-header.liquid`**: Sticky navigation header with custom menu linklists and Call-to-Actions (CTAs).
- **`sections/walbayzon-hero.liquid`**: High-conversion hero section featuring custom highlights, ratings, and glowing backdrops.
- **`sections/walbayzon-marquee.liquid`**: Auto-scrolling logo marquee highlighting dominated marketplaces.
- **`sections/walbayzon-services.liquid`**: Clean grid showing agency core services and capabilities.
- **`sections/walbayzon-stats.liquid`**: Highlights key results and agency metrics with coffee-colored gradient themes.
- **`sections/walbayzon-process.liquid`**: A horizontal 4-step discovery/deployment process flow.
- **`sections/walbayzon-testimonials.liquid`**: A grid layout displaying client testimonials, rating stars, and roles.
- **`sections/walbayzon-mastercourse.liquid`**: High-conversion mastercourse CTA featuring duration badges, pricing, and perks checklists.
- **`sections/walbayzon-footer.liquid`**: Beautiful corporate footer featuring large watermark text and link lists.
- **`sections/walbayzon-full-landing.liquid`**: An all-in-one section file. **Upload this single file** if you want to deploy the complete landing page in a single section card on any page.

---

## 🚀 How to Install & Use on Shopify

### Method 1: Installing Individual Sections (Recommended for Modular Layouts)
1. Log into your **Shopify Admin**.
2. Go to **Online Store > Themes**.
3. Next to your active theme, click the **three dots (...)** and select **Edit Code**.
4. In the left panel, scroll down to the **Sections** folder and click **Add a new section**.
5. Name the section (e.g. `walbayzon-hero`) and click **Create Section**.
6. Copy the code from the corresponding `.liquid` file in this folder and paste it into Shopify (replacing everything).
7. Repeat this for all other sections you wish to use.
8. Click **Save** in the top right.

### Method 2: Installing the All-in-One Page Section
1. Under the **Sections** folder, click **Add a new section**.
2. Name it `walbayzon-full-landing`.
3. Copy the code from [walbayzon-full-landing.liquid](file:///Users/ajay/Desktop/Projects/walbazyon/workflow/sections/walbayzon-full-landing.liquid) and paste it into Shopify.
4. Click **Save**.

---

## 🎨 Configuration inside Theme Editor
1. Go to **Online Store > Themes** and click **Customize** on your theme.
2. In the top dropdown, select the page you want to place the sections on (e.g., **Home page**, or create a new **Page** template).
3. In the sidebar, click **Add Section** and search for `Walbayzon`.
4. Click on the sections (e.g., `Walbayzon Hero`, `Walbayzon Services`) to insert them into your layout.
5. Click on each section in the sidebar to open the settings panel. You can configure:
   - Announcement Text, Button Labels, and Colors.
   - Logo letters/text and Navigation Linklists.
   - Testimonial quotes and author names.
   - Sourcing and performance stats.
   - Tailwind settings (with Preflight disabled so your main theme doesn't break).
