# Shaiglo Luxury Website, Version 8

This is the complete original Version 8 HTML website for review on GitHub Pages, not the incomplete WordPress conversion.

## Publish on GitHub Pages
1. Create a **new public repository** named `shaiglo-preview` in the intended GitHub account. Do not use an unrelated existing repository.
2. Upload `index.html` and `.nojekyll` from this folder to the repository root. Commit the files to `main`.
3. Go to **Settings > Pages**. Under Build and deployment, select **Deploy from a branch**, `main`, `/ (root)`, and Save.
4. GitHub displays the public URL on that same Pages settings screen. It will generally have the form `https://YOUR-USERNAME.github.io/shaiglo-preview/`.
5. Share that URL to review all pages by clicking the site's navigation links. The site uses hash routes, such as `#shop`, `#story`, and `#journal`, all within the same index.html.

## What's included
The full responsive site from the approved HTML: Home; Shop; Our Story; Skincare Blog and article; Contact; FAQs; Shipping; Returns; Payments; Privacy; Terms; bag/account previews; and nine product details.

## Important preview limitations
- Several images and the film source load from `shaiglobeautycare.com`. If those files change or are unavailable, their visuals may not render. Other images are embedded inside the HTML.
- The contact form opens the visitor's email app using `mailto:`. It does not send a message through a backend.
- Product checkout links open the existing Shaiglo storefront; no transactions are processed on GitHub Pages.
- Two ritual set prices are requested from the live WooCommerce public Store API. If blocked, the page displays a link to check the current price instead.
- This repository is a public preview of the design, not a production WooCommerce replacement. No changes to the existing WordPress site are needed.
