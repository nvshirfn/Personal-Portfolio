# My Personal Portfolio Website

🌐 **Live Site:** [https://nvshirfn.github.io/Personal-Portfolio/](https://nvshirfn.github.io/Personal-Portfolio/)

A multi-page personal portfolio website I built as coursework for **CSC574 - Dynamic Web Application Development** at Universiti Teknologi MARA (UiTM), Cawangan Perak, Kampus Tapah.

---

## About

This is my personal profile and portfolio website. I built it to showcase my biography, academic timetable, photo galleries, and to demonstrate sign-in/sign-up forms with client-side validation.

---

## Pages

| Page | Description |
|---|---|
| `index.html` | Home — my landing page with a typing animation cycling through my roles |
| `biography.html` | About Me — my personal background and introduction |
| `timetable.html` | My weekly class schedule with clickable course details |
| `slideshow.html` | My image gallery with an auto-advancing slideshow |
| `download.html` | My download centre for my academic calendar PDF |
| `links.html` | Links I find useful — UiTM, KPPIM, i-Student |
| `contact.html` | My contact information |
| `signinjs.html` | Sign-In form with my own client-side validation |
| `signupjs.html` | Sign-Up form with my own client-side validation |
| `signout.html` | Sign-Out confirmation page |
| `disclaimer.html` | My disclaimer and terms of use |

---

## Features

- Responsive layout with mobile-friendly navigation
- Typing animation on the home page cycling through developer roles
- Auto-advancing image slideshow with manual prev/next controls
- Client-side form validation (required fields, email format, password length, password match)
- Interactive timetable using CSS `:target` — click a subject to reveal course and lecturer details
- Consistent dark theme (`#000000` background, `#87CEEB` sky-blue accents) across all pages
- Social media links (LinkedIn, Instagram, YouTube) on every page

---

## Tech Stack

- **HTML5**
- **CSS3** (Flexbox, Grid, CSS animations, media queries)
- **Vanilla JavaScript** (form validation, slideshow logic)
- **Font Awesome 6.4** — icons
- **Google Fonts** — Poppins

> No frameworks, libraries, or backend — fully static.

---

## Project Structure

```
profile/
├── index.html
├── biography.html
├── timetable.html
├── slideshow.html
├── download.html
├── links.html
├── contact.html
├── signinjs.html
├── signupjs.html
├── signout.html
├── loginsuccess.html
├── signupsuccess.html
├── disclaimer.html
├── style.css
├── kalender-akademik.pdf
└── pictures/
    ├── logo.png
    ├── gmbr1.jpg
    ├── gmbr2.jpg
    ├── cat.jpg
    ├── deanlist.jpg
    ├── parents.jpg
    ├── raya.jpg
    ├── sem1.jpg
    └── trip.jpg
```

---

## How to Run

No build step required. Open `index.html` directly in any modern browser, or serve the folder with any static file server:

```bash
# Using VS Code Live Server, or:
npx serve .
```

---

## Course Info

| | |
|---|---|
| **Course** | CSC574 - Dynamic Web Application Development |
| **Institution** | Universiti Teknologi MARA (UiTM), Cawangan Perak, Kampus Tapah |
| **Lecturer** | Madam Siti Rozanae Binti Ismail |
| **Student** | Muhammad Danish Irfan Bin Muhaizul |

---

&copy; 2025 Danish. All rights reserved.
