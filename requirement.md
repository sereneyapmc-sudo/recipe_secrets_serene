# Recipe Secrets Restaurant — Website Content

Five-page site: **Home · About · Specials · Reservation · Contact**

> Items marked **[PLACEHOLDER]** need real details before the site goes public.

---

## 1. Home

**Tagline:** Family recipes, cooked fresh daily

# Every dish starts with a handwritten recipe.

We cook from a collection of family recipe cards, some three generations old. Slow stocks, spice pastes ground in-house, and bread baked every morning.

**Buttons:** [Book a table] → Reservation · [See this week's specials] → Specials

### Featured recipe card: House Braised Beef Rendang
1. Grind chilli, galangal, lemongrass
2. Toast kerisik until deep gold
3. Simmer in coconut milk, 4 hours
4. Rest overnight, never skip this

*Handwritten note: "the secret is step 4!"*

### Quick facts
| | |
|---|---|
| **40+ recipes** | from our family collection on the menu |
| **4-hour stocks** | made from scratch every morning |
| **New specials** | every week, chosen by the head chef |

---

## 2. About

**Eyebrow:** Our story

# A box of recipe cards, and a kitchen to cook them in

Recipe Secrets began with a shoebox of stained index cards: dishes written down by grandparents, aunties and old neighbours, each with notes scribbled in the margins about what really made them work.

We opened the restaurant to cook those recipes the way they were meant to be cooked. No shortcuts, no premixes. If a recipe says to rest the curry overnight, we rest it overnight.

Today our kitchen team still works from those cards, and we add a new one whenever a guest or staff member shares a family dish worth keeping.

> "A recipe is only a secret until you share it at the table."

### What we stand for
- **From scratch** — Sauces, pastes, stocks and breads are made in our kitchen every day.
- **Seasonal** — We buy from local markets and change our specials with what is good that week.
- **Generous** — Portions made for sharing, the way family meals are served at home.
- **Welcoming** — Families, couples, friends and large groups. Children always welcome.

*[PLACEHOLDER — replace with the restaurant's real founding story]*

---

## 3. Specials

**Eyebrow:** This week's specials

# Pulled from the recipe box this week

Available while they last, lunch and dinner. Ask your server about allergens.

| Recipe card | Dish | Description | Details | Price |
|---|---|---|---|---|
| No. 07 | Grandma's Beef Rendang | Slow-braised beef shin in a dry coconut and spice paste, served with turmeric rice and achar. | Serves 2 · Cooked 4 hrs · Spicy | S$28 |
| No. 12 | Ginger-Scallion Steamed Barramundi | Whole local barramundi, light soy, sizzled ginger and scallion oil. Best with plain rice. | Serves 2–3 · Steamed to order | S$32 |
| No. 21 | Mushroom & Barley Risotto | Pearl barley cooked slowly in mushroom stock, finished with brown butter and toasted walnuts. | Serves 1 · Vegetarian | S$22 |
| No. 33 | Pandan Gula Melaka Cake | Soft pandan sponge layered with palm sugar cream, made fresh every morning. | Dessert · Contains nuts | S$9 |

### Weekly deals
- **Tuesday** — Free dessert for birthday guests
- **Wednesday** — Kids eat free with every adult main
- **Friday** — Chef's tasting set, 5 courses, S$68
- **Sunday** — Family brunch, 10am to 2pm

*[PLACEHOLDER — confirm dishes, prices and deals]*

---

## 4. Reservation

**Eyebrow:** Reservations

# Book your table

Groups of 10 or more, please call us so we can set up the right space.

### Booking form fields
| Field | Type | Required |
|---|---|---|
| Name | Text | Yes |
| Phone | Phone | Yes |
| Email | Email | No |
| Date | Date picker (today onwards, Mondays blocked) | Yes |
| Time | 11:30am – 9:00pm, every 30 min (default 7:00pm) | Yes |
| Guests | 1–9 (default 2) | Yes |
| Occasion | None / Birthday / Anniversary / Business / Family gathering | No |
| Special requests | Free text (allergies, high chair, seating) | No |

**Button:** Request booking

**Confirmation message:** "Booking request ready. We will call or message you to confirm your table within a few hours." Shows a summary of the guest's details.

*Side note:* "Tip: Friday tasting nights fill up fast, book early!"

> **To go live:** connect the form to a booking system (Chope, Quandoo, SevenRooms) or a Jotform / Google Form that notifies the restaurant.

---

## 5. Contact

**Eyebrow:** Contact

# Come hungry, or just say hello

- **Address:** 12 Recipe Lane, #01-01, Singapore 089000 *[PLACEHOLDER]*
- **Phone:** +65 6123 4567 *[PLACEHOLDER]*
- **Email:** hello@recipesecrets.sg *[PLACEHOLDER]*
- **Getting here:** 5 minutes' walk from the nearest MRT station. Street parking and a public car park nearby. *[PLACEHOLDER — name the MRT station]*
- **Private events:** Our back room seats up to 30 for birthdays, company dinners and family gatherings. Email us with your date and group size.

### Opening hours *[PLACEHOLDER]*
| Day | Hours |
|---|---|
| Monday | Closed |
| Tuesday | 11:30am – 10pm |
| Wednesday | 11:30am – 10pm |
| Thursday | 11:30am – 10pm |
| Friday | 11:30am – 11pm |
| Saturday | 10am – 11pm |
| Sunday | 10am – 9pm |

### Message form
Fields: Name · Email · Message → **Send message**

---

## Footer
© 2026 Recipe Secrets Restaurant · Cooked from the recipe box, served with love.

---

## Launch checklist
- [ ] Replace all [PLACEHOLDER] details (address, phone, email, hours, story, menu)
- [ ] Add 4–6 real food and interior photos
- [ ] Connect the reservation and contact forms to a booking system or email
- [ ] Register a domain (e.g. recipesecrets.sg) and choose hosting (Netlify, Vercel, Wix)
- [ ] Add Google Maps link and Google Business Profile
- [ ] Link Instagram / You are building a website for "Recipe Secrets Restaurant". Please read this whole brief, then show me a short plan (file structure + design direction) before writing code.

## Goal
A simple, warm, mobile-first restaurant website that makes people want to visit, and makes it easy to book a table.

## Tech constraints
- Plain vanilla HTML, CSS and JavaScript only. No frameworks, no build step, no npm.
- Must run by simply opening index.html, and deploy as-is to free static hosting (GitHub Pages, Netlify or Cloudflare Pages).
- One shared stylesheet (css/style.css) and one shared script (js/main.js).
- Use relative paths everywhere so it works in a subfolder on GitHub Pages.

## Pages (exactly 5)
1. index.html — Home
   - Hero section with restaurant name, tagline, hero image, and two buttons: "Reserve a Table" and "See Today's Specials"
   - Short intro (2–3 lines), 3 highlight cards (e.g. signature dishes), opening hours, location snippet
2. about.html — About
   - Our story, the chef/founder, what makes our recipes special, photo placeholders
3. specials.html — Specials
   - Specials load from a single file: data/specials.json (name, description, price, image, available days, tags like "Chef's pick" or