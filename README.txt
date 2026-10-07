ANANDA WEDDING & CONFERENCE VENUE - DEMO WEBSITE

HOW TO OPEN: unzip, then double-click index.html. It runs in any browser, no internet needed
(except the Google Fonts, which fall back to system fonts if offline).

HOW TO EDIT: open index.html in a text editor (VS Code, Notepad++).
Everything client-specific is in the CONFIG block near the top of the <script> section:
phone, WhatsApp, email, address, social links, hero slides, gallery and photos.
Search for "CLIENT TO CONFIRM" to find items Ananda must confirm before launch.

ADDING PHOTOS: put photos in the same folder (e.g. images/chapel.jpg), then in CONFIG:
  images:{ intro:'images/garden.jpg', w1:'images/chapel.jpg', v1:'images/gardens.jpg' }
  hero:[{img:'images/hero1.jpg', h:'...', p:'...'}, ...]
  gallery: set img:'images/xyz.jpg' on each item.
Empty values keep the illustrated placeholder.

HOSTING: upload this folder to any web host (Netlify, Vercel, cPanel). index.html is the entry point.
