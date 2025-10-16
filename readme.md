# Neon Drift — JDM Creative Showcase

Author: Jeremy (J3RRY)  
**Project Type:** Final Independent Web Project  
**Technologies:** HTML • CSS • JavaScript (LocalStorage)

---

## 🚗 Project Overview

**Neon Drift** is a fantasy-themed web application combining **anime aesthetics** with **JDM (Japanese Domestic Market) car culture**.  
It demonstrates:

✅ Semantic **HTML structure**  
✅ Responsive **CSS (Grid / Flexbox + Media Queries)**  
✅ **JavaScript** DOM Manipulation  
✅ **Form Validation **  
✅ **localStorage-based Data Persistence**  
✅ **Navigation between 3 linked pages**

Users can:

1. **Add their favorite anime/JDM cars** via a form (`contact.html`)
2. **Save them to `localStorage`**
3. **View & manage** them on (`index.html`)
4. **See a summary** on (`about.html`)

---

## 📂 Project Structure

1. index.html → Home / Showcase Page
2. about.html → About / Summary Page
3. contact.html → Add Car Form Page
4. style.css → Neon Anime/JDM Theme
5. app.js → Core JavaScript  (storage &DOM)
6. README.md → Documentation
7. /assets → Placeholder images (Anime × JDM)

---

## 💾 Local Storage Data Format

Each saved car entry looks like:

{
  "id": 1690000000000,
  "title": "S13 Drift",
  "model": "Nissan Silvia S13",
  "category": "jdm",
  "image": "https://...",
  "notes": "Wide body / anime livery",
  "createdAt": "2025-10-11T..."
}
✅ Rubric Compliance
Requirement	Implemented

Semantic HTML	            ✔ Yes
3 Linked Pages   	        ✔ index / about / contact
Responsive Design	        ✔ Media Queries + Flexbox/Grid
DOM Manipulation	        ✔ Rendering + Edit/Delete
Event Handling	            ✔ Form + Buttons + Slider Controls
Validation & Error Handling	✔ Contact Form
Data Persistence	        ✔ localStorage
Usability	                ✔ Clear UI, Neon Theme
Documentation	            ✔ This README
Git Commits	                ✔ recorded below

Commit Messages

1. init: add project scaffold (index, about, contact, style.css, app.js, README)

2. feat: add hero slider to index

3. style: create neon anime/JDM theme in style.css

4. feat: implement add form (contact.html) structure

5. feat: localStorage helpers getItems/saveItems

6. feat: add client-side validation for add form

7. feat: render saved items on index.html

8. feat: render saved items summary on about.html

9. fix: add edit & delete handlers to cards

10. feat: hero controls (prev/next)

11. style: responsive adjustments

12. accessibility: add ARIA labels and roles

13. docs: add README.md initial draft

14. test: add sample placeholder images to assets

15. fix: improve error messages on form

16. perf: use document fragments to render grids

17. style: tweak card hover & focus states

18. docs: add usage & data model to README

19. chore: update index title and meta

20. feat: add nav highlighting for active page

21. fix: handle empty image gracefully

22. test: add seeded demo items script (optional)

23. style: adjust hero layout for small screens

24. docs: finalize README and rubric mapping


25. chore: prepare for submission (clean unused assets)


