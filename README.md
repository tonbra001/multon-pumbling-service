Moulton Plumbing & Heating — Website
A demo website for Moulton Plumbing & Heating Ltd, a gas and heating engineer based in Moulton, Northampton (NN3 7BY). Built as an example to show the business what a website could look like for them, using details from their public Google Maps listing (address, phone, hours, and their two real customer reviews).
Pages
index.html — Home
services.html — Services
about.html — About
contact.html — Contact

All four share the same header, footer, and styling from assets/style.css, plus a small mobile nav toggle in assets/nav.js.
Structure
index.html

services.html

about.html

contact.html

assets/

  style.css

  nav.js

Keep assets as a folder, not loose files at the top level, or the pages will load without styling or the mobile menu.
Viewing it
Open index.html in any browser. Every link between pages is relative, so it works straight off the file system with no server needed. It needs an internet connection once to pull the Google Fonts used for the headings and body text.
