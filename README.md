# Alpha ledger | Manga Halftone Edition

A comic/manga-styled, offline-first financial ledger web application built for students to track monthly tuition fees, manage teacher payments, and maintain secure records. Featuring a distinct neo-brutalist halftone aesthetic, it combines robust offline capabilities with seamless cloud synchronization.

---

## 🚀 Key Features

* **Manga Halftone Aesthetic:** Custom-styled UI featuring bold borders, halftone dot patterns, glassmorphic floating navbars, and comic shadow accents.
* **6-Digit PIN Authentication:** Secure, code-locked entry system utilizing visual pin indicators and a custom on-screen numeric keypad.
* **Offline-First JSON Storage:** Built-in IndexedDB persistence layer that allows full offline usage with an automatic queue sync mechanism when connection is restored.
* **Teacher Fee Management:** Track pending (due) and completed monthly teacher payments, calculate totals, and update statuses instantly.
* **Profile & Account Customization:** Manage custom student names, class streams, avatar pictures, and switch accounts or update access codes seamlessly.
* **Firebase Integration:** Real-time cloud backup and multi-device synchronization via Google Cloud Firestore.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript (ES Modules)
* **Icons & Fonts:** FontAwesome 6, Google Fonts (*Bangers* & *Plus Jakarta Sans*)
* **Database & Storage:** Firebase Firestore & Local IndexedDB (JSON storage layer)

---

## 📁 Project Structure

```text
alpha-ledger/
├── index.html       # Complete single-file application source code
├── data.json        # Sample JSON database schema & template
└── README.md        # Project documentation
