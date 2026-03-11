# AIU-Mart
HCI usability testing demo site with intentional UX issues for Think-Aloud Protocol sessions — Asia-Pacific International University.

# 🛍️ AIU-Mart — Usability Testing Demo

> A purpose-built e-commerce demo website for the **Human Computer Interaction** course at Asia-Pacific International University (APIU).

---

## 📌 Overview

**AIU-Mart** is a simulated fashion e-commerce website designed exclusively for classroom usability testing exercises. It replicates the look and feel of a real online shop while containing a set of **intentional UX design flaws** — making it an ideal subject for both **Heuristic Evaluation** and **Think-Aloud Protocol** sessions.

Students interact with the site as real users, uncovering usability issues through structured testing activities.

---

## 🎓 Course Information

| | |
|---|---|
| **Course** | Human Computer Interaction |
| **Institution** | Asia-Pacific International University (APIU) |
| **Topic** | Think-Aloud Protocol & Usability Testing |
| **Prerequisite** | Heuristic Evaluation |

---

## 🌐 Live Demo

🔗 **[https://your-deployment-link-here](https://your-deployment-link-here)**

> Replace the link above with your GitHub Pages or Vercel URL after deployment.

---

## 🗂️ Site Structure

The site simulates a complete e-commerce shopping flow across five pages:

```
Home
 └── Catalog (All Products)
      └── Product Detail Page
           └── Shopping Cart
                └── Checkout
                     └── Order Confirmation
```

---

## 🐛 Intentional Usability Issues

The following UX problems are deliberately embedded in the site. Students are expected to discover these through usability testing — **do not share this list with participants before a session.**

| # | Location | Issue | Nielsen's Heuristic |
|---|---|---|---|
| 1 | Product Cards | "+" button used instead of "Add to Cart" | H6 — Recognition over Recall |
| 2 | Navigation | Cart item count badge is too small to notice | H1 — Visibility of System Status |
| 3 | Product Detail | Button says **"Add to Bag"** (inconsistent with industry standard) | H4 — Consistency & Standards |
| 4 | Product Detail | Both **"Save for Later"** and **"Add to Wishlist"** exist with no clear difference | H4 — Consistency & Standards |
| 5 | Product Detail | Quantity control is very small and visually de-emphasised | H8 — Aesthetic & Minimalist Design |
| 6 | Product Detail | XXL size appears the same as others but is unavailable | H1 — Visibility of System Status |
| 7 | Cart | Promo code field is hidden inside a collapsed accordion | H6 — Recognition over Recall |
| 8 | Cart | Checkout button labelled **"Proceed"** — destination unclear | H2 — Match Between System & Real World |
| 9 | Checkout | **"Contact"** field label is ambiguous (email or phone?) | H2 — Match Between System & Real World |
| 10 | Checkout | **"Priority"** shipping option is unexplained | H10 — Help & Documentation |
| 11 | Checkout | Final button says **"Confirm Order"** — unclear if payment is charged immediately | H1 — Visibility of System Status |
| 12 | Catalog | Sort dropdown is labelled **"Arrange By"** instead of "Sort By" | H4 — Consistency & Standards |

---

## 📋 Suggested Test Tasks

Use these tasks during Think-Aloud Protocol sessions. Tasks are written as **scenarios** — they describe a goal, not the steps.

### Task 1 — Simple
> *"You want to browse the store and find a dress you like. Look around and tell me what you notice."*

### Task 2 — Medium
> *"You want to buy a Canvas Sneakers. Find them, choose your size, and add them to your cart."*

### Task 3 — Complex
> *"You have a promo code: SAVE10. You want to use it before completing your purchase. Go ahead and check out."*

### Task 4 — Error Recovery
> *"You added an item to your cart but changed your mind. Remove it and continue shopping."*

---

## 👥 Classroom Activity Roles

Each group of 3 students takes on the following roles and rotates each round:

| Role | Responsibility |
|---|---|
| **Participant (User)** | Performs tasks and thinks aloud throughout |
| **Facilitator** | Reads task cards, prompts participant to keep talking, does not assist |
| **Observer** | Records verbal comments, hesitations, errors, and emotional reactions |

---

## 🧪 Session Protocol

### Before the Session
- Ensure the device can access the live demo link
- Print task cards and observation sheets
- Brief the facilitator: they must not help the participant

### Opening Script (read by Facilitator)
> *"Thank you for participating. We are testing the website, not you — there are no wrong answers. As you complete each task, please say out loud everything you are thinking, even if it seems unimportant. I will read you a task and you may begin whenever you are ready. I cannot help during the task, but I will remind you to keep talking if you go quiet."*

### Prompt if Participant Goes Silent
> *"Can you tell me what you are thinking right now?"*

---

## 🔗 Connection to Heuristic Evaluation

This site is designed to bridge two key usability methods:

- In **Heuristic Evaluation**, students identify problems as **UX experts** using Nielsen's 10 heuristics.
- In **Think-Aloud Protocol**, students observe **real users** discovering problems naturally.

After testing, students compare their findings from both methods and reflect on the differences.

---

## 🛠️ Technical Details

| | |
|---|---|
| **Type** | Single-page HTML application |
| **Dependencies** | None (no frameworks, no backend) |
| **Fonts** | Google Fonts — Playfair Display, DM Sans |
| **Hosting** | GitHub Pages / Vercel (static) |
| **File** | `index.html` |

---

## 🚀 Deployment

### GitHub Pages
1. Upload `index.html` to a public GitHub repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at `https://yourusername.github.io/repository-name/`

### Vercel
1. Log in at [vercel.com](https://vercel.com)
2. Click **Add New → Project**
3. Drag and drop the folder containing `index.html`
4. Click **Deploy**

---

## ⚠️ Disclaimer

This website is a **fictional prototype** created solely for educational purposes within the Human Computer Interaction course. All products, brands, prices, and order details shown are simulated and not real. No actual transactions are processed.

---

## 📄 License

This project is intended for **educational use only** within Asia-Pacific International University. Not for commercial distribution.

---

*Developed for the Human Computer Interaction course — Asia-Pacific International University (APIU)*
