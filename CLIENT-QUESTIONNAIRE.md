# MRS Hobby - Implementation Questionnaire

**Please answer these questions before we begin development. This ensures we build exactly what you need the first time.**

---

## General / Platform Questions

### 1. BigCommerce Store Details
- [ ] What BigCommerce plan are you on? (Standard, Plus, Pro, Enterprise)
- [ ] Current theme name:
- [ ] Can we get admin access or just API credentials?
- [ ] What apps/integrations are currently installed?

### 2. Timeline & Budget
- [ ] Do you have a target launch date?
- [ ] Preferred rollout: All at once or phased by priority?
- [ ] Any budget constraints per feature?

---

## Menu Designs (High Priority) ✅ *Mockup Ready*

### 3. Menu Implementation
- [ ] Have you reviewed and approved the menu mockup?
- [ ] Any changes needed before implementation?
- [ ] Do you want product images/featured items in mega menu dropdowns?
- [ ] Should menu auto-update when new categories are added?

---

## New Arrivals Page (High Priority) ✅ *Mockup Ready*

### 4. New Arrivals Definition
- [ ] What defines "new"? (Last 30 days, 60 days, manual tagging?)
- [ ] Should it auto-populate or allow manual curation?
- [ ] Minimum number of products before page goes live?
- [ ] Sort by: Date added, Price, Popularity, Alphabetical?

### 5. New Arrivals Approval
- [ ] Have you reviewed and approved the New Arrivals page mockup?
- [ ] Any design changes needed?

---

## Tutorials Page (As Time Allows) ✅ *Mockup Ready*

### 6. Tutorial Content
- [ ] Do you have all video links ready? (YouTube, Vimeo, other?)
- [ ] How many tutorials to start with?
- [ ] Categories for tutorials? (Beginner, Advanced, Product Type, Brand?)
- [ ] Who will add new tutorials? (You update, or you need admin panel?)

### 7. Tutorials Approval
- [ ] Have you reviewed and approved the Tutorials page mockup?
- [ ] Any design changes needed?

---

## Homepage Banners (Medium Priority)

### 8. Banner Management
- [ ] Who creates banner graphics? (Designer, or you provide?)
- [ ] What sizes/dimensions are needed?
- [ ] Do you want to update banners yourself (admin UI) or have us update them?
- [ ] Static banners or rotating carousel?
- [ ] How many banner slots needed? (Mobile: ___ Desktop: ___)

### 9. Video Banners
- [ ] Where will videos be hosted? (YouTube, Vimeo, self-hosted?)
- [ ] Video file sizes/format?
- [ ] Autoplay video or click-to-play?
- [ ] Muted by default?

### 10. Full Bleed Layout
- [ ] Preferred approach: Full bleed banners OR side menu as overlay?
- [ ] Keep logo/search visible at top?

---

## Automate Brand/Category Linking (High Priority)

### 11. Product Import Process
- [ ] How do new products get added? (CSV import, manual, supplier feed?)
- [ ] What data comes with new products? (Title, SKU, description, images?)
- [ ] Are brand names in product titles? (Example: "Tamiya Acrylic Paint")
- [ ] List of all brands you carry: (or provide separate doc)

### 12. Category Structure
- [ ] Provide your current category tree/hierarchy?
- [ ] Are categories based on: Product type, Brand, Scale, Material, Use case?
- [ ] Should products auto-assign to multiple categories?

### 13. Matching Rules
- [ ] Match by: Keywords in title, SKU pattern, supplier data?
- [ ] What happens if brand/category can't be auto-detected? (Flag for manual review?)
- [ ] Do you have a fallback category? (Example: "Uncategorized New Arrivals")

---

## Back in Stock Alerts (High Priority)

### 14. Notification System
- [ ] Notification method: Email only or Email + SMS?
- [ ] Email service: Use your current email or integrate with Mailchimp/SendGrid?
- [ ] Who gets admin notification when customer signs up?

### 15. Pre-Order Functionality
- [ ] Can customers pre-order out-of-stock items or just get notified?
- [ ] If pre-order: Payment upfront or deposit?
- [ ] How long before expected restock date to allow pre-orders?

### 16. Stock Sync
- [ ] Is BigCommerce inventory accurate and real-time?
- [ ] Do you manually update stock levels or automated?

---

## Loyalty Points Display (High Priority)

### 17. Loyalty System
- [ ] What loyalty app/system are you using? (BigCommerce built-in, Yotpo, Smile.io, custom?)
- [ ] Do you have API access to loyalty data?
- [ ] Customer login: Phone number only or also email/password?

### 18. Points Display
- [ ] Where should points show? (Account dashboard only, or also in header/cart?)
- [ ] Show points balance only or also: Points earned, Points redeemed, Points expiring?
- [ ] Allow customers to redeem points directly in app?

---

## Birthday Loyalty Reminders (Medium Priority)

### 19. Birthday Data
- [ ] Do you currently collect customer birthdates? (Required or optional at signup?)
- [ ] If not collected: Should we add birthday field to account creation?
- [ ] Privacy: Customers must opt-in to birthday reminders?

### 20. Notification Timing
- [ ] When to add birthday points? (On birthday, day before, week before?)
- [ ] Expiration warning: How many days before expiration? (3 days, 7 days, 14 days?)
- [ ] Email template: Use existing loyalty email design or create new?

---

## Email Newsletter Popup (Medium Priority)

### 21. Mailchimp Integration
- [ ] Do you have a Mailchimp account? (API key ready?)
- [ ] Which Mailchimp list/audience to add subscribers to?
- [ ] Tag new subscribers? (Example: "Website Popup")

### 22. Popup Behavior
- [ ] When should popup appear? (Immediate, 5 seconds delay, on exit intent, on scroll?)
- [ ] Offer incentive for signup? (Discount code, free shipping, etc.)
- [ ] "3 times" limit: Per user ever, per session, per 30 days?
- [ ] Cookie duration: 30 days, 90 days, 1 year?

### 23. Popup Design
- [ ] Do you have a design mockup or use a simple/clean default?
- [ ] What text/message should it display?
- [ ] Single-field (email only) or also collect name?

---

## Out of Stock Banner (As Time Allows)

### 24. Homepage Banner
- [ ] Placement: Top of homepage, sidebar, footer?
- [ ] Always visible or only when there are out-of-stock high-demand items?
- [ ] Link to: Dedicated page listing all out-of-stock items or back-in-stock signup form?

---

## APP: Special Orders (Custom App)

### 25. App Architecture
- [ ] Preferred: BigCommerce custom app (OAuth) or standalone web form?
- [ ] Where to host? (Railway, Vercel, your server?)
- [ ] Database: PostgreSQL, Firebase, Google Sheets (simple)?

### 26. Customer Workflow
- [ ] How does customer find this feature? (Product page button, menu link, separate page?)
- [ ] Customer submits request → Instant quote or "we'll get back to you"?
- [ ] Payment timing: Upfront or after quote approval?

### 27. PayPal Integration
- [ ] PayPal Business account email:
- [ ] One-time payment or deposit + balance due later?
- [ ] Refund policy if item can't be fulfilled?

### 28. Address Verification
- [ ] Which service? (USPS API, SmartyStreets, Google Maps Autocomplete?)
- [ ] What if address invalid: Reject order or allow customer override?

### 29. Admin Management
- [ ] How to manage incoming special orders? (Email notifications, admin dashboard, integration with existing system?)
- [ ] Who handles fulfillment? (You order from supplier, dropship, other?)
- [ ] Order tracking: Integrate with BigCommerce orders or separate system?

### 30. Shipping
- [ ] Customer sees shipping quote before payment?
- [ ] Flat rate, calculated, or quoted after submission?

---

## APP: Item Not Carried (Custom App)

### 31. Scope
- [ ] What types of items? (RC cars, specific brands, special imports?)
- [ ] Price range expectations?
- [ ] Typical lead time to source items?

### 32. Customer Request Flow
- [ ] Customer provides: Item name/link/photo + desired quantity?
- [ ] Quote process: Immediate estimate or manual quote?
- [ ] Payment: Same as Special Orders or different?

### 33. Admin Workflow
- [ ] How do you source these items? (Specific suppliers, wholesale platforms, other retailers?)
- [ ] Track requests in: BigCommerce, separate dashboard, email?

---

## Final Questions

### 34. Mobile App vs Mobile Web
- [ ] You mention "MOBILE APP" throughout. Do you mean:
  - **Mobile-responsive website** (works on phone browsers)?
  - **Native mobile app** (download from App Store/Google Play)?
  - **Progressive Web App (PWA)** (installable but still web-based)?

### 35. Social Media Shops
- [ ] Which platforms? (Facebook Shop, Instagram Shop, TikTok Shop?)
- [ ] Already set up or need help integrating?

### 36. Testing & Approval
- [ ] Who will test features before going live? (You, specific team members?)
- [ ] Staging site available or test on live store?

---

## Next Steps

**After completing this questionnaire:**

1. We'll review your answers and identify any follow-up questions
2. Create a detailed development plan with timeline estimates
3. Get your approval on plan and timeline
4. Begin development in priority order

**Please return completed questionnaire to:** [Your email/contact info]

**Questions?** Contact Adam at [contact info]

---

**Thank you!** These answers will help us build exactly what MRS Hobby needs.
