# Front-End Web Design Projects

Three static websites built with **HTML and CSS** as a screenshot portfolio.

| | |
|---|---|
| **Name** | Sindhura A |
| **Roll No.** | 26001056 |
| **Branch** | CSM (AI and ML) |
| **Section** | 4 |
| **Year** | 2026 |

---

## Projects at a glance

| # | Project | Type | Theme | HTML | CSS |
|---|---------|------|-------|------|-----|
| 1 | **VELORA** | Shopping website | White and purple | `SHOPPING.html` | `SHOPPING.css` |
| 2 | **TRAVELORA** | Bus and train ticket booking | Navy and blue | `TRAVEL.html` | `TRAVEL.css` |
| 3 | **SweetBites** | Bakery and cake studio | Chocolate brown and peach | `BACKERY.html` | `BACKERY.css` |

A screenshot walkthrough of all three is in **`Web_Design_Projects.pdf`** (23 screens).

---

## 1. VELORA: Shopping Website
*"Find your everyday magic."*

An online store for fashion, electronics, beauty products and accessories.

**Features**
- Sale banner and sticky navigation with search, cart and account icons
- Hero section with two action buttons and a happy-shoppers badge
- Service highlights: free delivery, easy returns, secure shopping, friendly support
- Shop by Category cards (Fashion, Electronics, Beauty, Accessories)
- Best Picks product grid with category filters, discount tags, ratings, old and new prices, and Add to Cart
- Newsletter sign-up and a footer with Explore, Customer Care and Get in Touch

**Fonts:** Playfair Display, DM Sans. **Icons:** Font Awesome 6.5.2

## 2. TRAVELORA: Bus and Train Ticket Booking
*"Every journey has a beautiful beginning."*

A step-by-step booking flow: search a route, compare fares, pick a seat and enter passenger details.

**Features**
- Hero section with a "Find a Trip" button
- Search form: travel type, from, to, journey date, passengers
- Sample bus and train service cards with times, duration, amenities, ratings and fares
- Fare comparison table
- Seat layout (available, selected, occupied) with a journey summary
- Passenger details form with required-field validation
- Call-to-action banner and footer

**Fonts:** Manrope, DM Sans. **Icons:** Font Awesome 6.5.2

> **Demo only.** All services, fares and times are sample data. No real ticket, reservation or payment is made.

## 3. SweetBites: Bakery and Cake Studio
*"Life is sweeter with something delicious."*

A warm, inviting site for a bakery with a menu, custom cakes, gallery and order enquiry.

**Features**
- Announcement bar (15% off first order) and hero with two buttons
- Category circles: Celebration Cakes, French Pastries, Cookies and More, Custom Creations
- About section and special offer banner
- Filterable menu of favourites (All, Cakes, Pastries, Cookies)
- Custom cake section with a "Design My Cake" button
- Photo gallery and customer testimonials
- Order enquiry form with address, phone, email and opening hours
- Newsletter sign-up and footer

**Fonts:** Playfair Display, DM Sans

> Testimonials and contact details are sample content.

---

## Folder structure

```
web-projects/
├── SHOPPING.html
├── SHOPPING.css
├── TRAVEL.html
├── TRAVEL.css
├── BACKERY.html
├── BACKERY.css
├── Web_Design_Projects.pdf
└── README.md
```

## How to run

1. Download or copy all files into one folder.
2. **Fix the CSS file links** (see the note below).
3. Double-click an `.html` file, or right-click it in VS Code and choose **Open with Live Server**.
4. Stay **online** while viewing: fonts, icons and images load from the internet.

### Important: CSS file names

Each HTML file links to its stylesheet under an older name. Either rename the CSS files or edit the `<link>` tag in each HTML file:

| HTML file | Currently links to | Your file is named |
|-----------|--------------------|--------------------|
| `SHOPPING.html` | `new.css` | `SHOPPING.css` |
| `TRAVEL.html` | `new2.css` | `TRAVEL.css` |
| `BACKERY.html` | `new3.css` | `BACKERY.css` |

Example fix in `SHOPPING.html`:

```html
<link rel="stylesheet" href="SHOPPING.css">
```

## Technologies used

- HTML5
- CSS3 (Flexbox, Grid, hover effects, responsive layout)
- Google Fonts
- Font Awesome icons (VELORA and TRAVELORA)

## Notes

- These are student front-end projects. There is no backend, database or payment system.
- Prices, ratings, contact details and reviews are placeholders for demonstration.
- Product and cake photos are loaded from online image links, so a few may not appear if a link breaks (for example, the sunglasses image in VELORA).

---

*Submitted by Sindhura A | Roll No. 26001056 | CSM (AI and ML), Section 4 | 2026*
