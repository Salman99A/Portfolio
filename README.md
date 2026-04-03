# salman.me

A **neo-brutalist interactive developer portfolio** built using **vanilla HTML, CSS, and JavaScript**.

No frameworks.  
No build tools.  
No dependencies.

This portfolio combines **bold neo-brutalist design**, an **interactive terminal interface**, and several **developer-style tools** such as weather lookup, calculator, and resume download.

Live Site  
https://salman.me

---

# About

This project is my **personal portfolio website** showcasing my work, journey, and skills as a **Full-Stack Developer**.

The website focuses on creating a **unique interactive experience** rather than a traditional static portfolio.

Visitors can explore the portfolio in two ways:

• Through the **neo-brutalist visual website**  
• Through a **developer terminal interface**

The goal was to build something that feels like **a developer’s workspace rather than a normal portfolio page**.

---

# Features

## Neo-Brutalist Portfolio Website

The main website uses **neo-brutalist design principles** including:

• Thick borders  
• High contrast colors  
• Offset box shadows  
• Exposed layout structure  
• Playful UI elements

Design elements used in the site include:

• Paper tear section dividers  
• Animated text highlights  
• Scroll-driven animations  
• Treasure map journey timeline  
• Decorative UI elements

---

## Interactive Terminal

The portfolio also includes a **terminal-style interface** where visitors can interact with the portfolio using commands.

Open:

```
/terminal.html
```

Example commands:

```
help
about
projects
weather mumbai
calc 80*9
pdf
```

Terminal features:

• Command parser  
• Command history navigation  
• Multiple terminal themes  
• Split terminal panes  
• Built-in calculator  
• Weather command  
• Resume download command  
• Snake game

---

# Terminal Commands

## Help

Displays all available commands.

```
help
```

---

## Weather

Fetches real-time weather information for any city.

Example:

```
weather mumbai
weather london
weather tokyo
```

Weather data uses:

• OpenStreetMap Nominatim (city → coordinates)  
• Open-Meteo API (weather data)

No API key required.

Example output:

```
Location: Mumbai
Temperature: 29°C
Wind: 9 km/h
```

---

## Calculator

A built-in calculator for evaluating mathematical expressions.

Example:

```
calc 80*9
```

Output:

```
🧮 80*9
= 720
```

Supported operators:

```
+  -  *  /  ( )
```

---

## Resume Download

Downloads the developer's resume.

```
pdf
```

Output:

```
Generating PDF resume...
Resume downloaded successfully.
```

The file downloaded is:

```
Salman_Ansari_Resume.pdf
```

---

# Design System

## Colors

| Color  | Variable   | Usage                |
| ------ | ---------- | -------------------- |
| Yellow | `--yellow` | Primary accent       |
| Cyan   | `--cyan`   | Code highlights      |
| Pink   | `--pink`   | Secondary accent     |
| Green  | `--green`  | Success indicators   |
| Black  | `--border` | Borders and outlines |

---

## Typography

Fonts used in the project:

Space Grotesk  
Space Mono  
Caveat

These fonts help combine **clean typography with handwritten UI elements**.

---

# Interactive Map

The portfolio includes an **interactive journey map** built using **Leaflet.js**.

Features:

• Custom styled map  
• Grid overlay  
• Marker locations  
• Timeline integration  
• Animated transitions

The map visualizes locations related to the developer's journey.

---

# Tech Stack

Frontend

HTML  
CSS  
JavaScript (Vanilla)

Libraries

Leaflet.js — interactive maps  
p5.js — Snake game  
Font Awesome — icons  
Google Fonts — typography

APIs

Open-Meteo — weather data  
OpenStreetMap Nominatim — geocoding

---

# Project Structure

```
.
├── index.html
├── terminal.html
├── script.js
├── neo-styles.css
├── styles.css
├── favicon.svg
├── Salman_Ansari_Resume.pdf
├── image/
│   ├── ARC-logo.png
│   ├── ARC-logo.svg
│   ├── avatar images
│   ├── pirate illustration
│   └── other assets
├── robots.txt
├── sitemap.xml
├── CNAME
├── LICENSE
└── README.md
```

---

# Run Locally

This project requires **no build tools**.

Simply run a static server.

Using Node:

```
npx serve .
```

Using Python:

```
python3 -m http.server 8000
```

Then open:

```
http://localhost:8000
```

---

# Author

Salman Ansari  
Full-Stack Developer

Co-Founder of **The ARC Studio**

Portfolio  
https://salman.me

---

# License

This project is **proprietary**.

You may view the source code for inspiration, but copying, modifying, or redistributing any part of this project without permission is not allowed.

See the LICENSE file for details.
