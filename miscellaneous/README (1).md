# 🍖 Steak House Website

## 📌 Overview
**Steak House** is a static website built with **HTML & CSS**to showcase a restaurant that serves ribs, wings, chips, and combos.  

The website highlights:
- 🥩 Signature meals (Ribs, Wings, Chips)  
- 🍗 Combos and pricing  
- 📖 Restaurant story & team  
- 📍 Location with Google Maps integration  
- 🔗 Social media links  

---

## 📂 Project Structure
```
steak-house/
│── /assests            # Images, videos, and logo
│── /css
│    └── style.css      # Main
Documentation
│── miscellaneous       # README.md
│──  /pages
│    ├── menu.html      # Menu page
│    ├── contact.html   # Contact page
│    └── about.html     # About Us page
│── index.html          # Homepage
```

---

## ✨ Features
✅ Responsive **navigation bar** with links to all pages  
✅ **Homepage** with video header, featured meals, gallery, and map  
✅ **Menu page** with detailed pricing for ribs, wings, chips, drinks, and combos  
✅ **Contact page** with review form + Google Maps embed  
✅ **About page** with restaurant story, mission, and team introduction  
✅ **Footer** with social media icons + quick navigation links  

---

## 🚀 How to Run
1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/steak-house.git
   ```
2. Open the folder and locate `index.html`.  
3. Double-click `index.html` OR open it in your browser.  
4. Make sure the `/assests` folder has all images and videos correctly linked.

---

## 🔧 Technologies Used
- 🌐 **HTML5**
- 🎨 **CSS3** (inline + internal styles)
- ⭐ **Font Awesome** for icons
- 🗺 **Google Maps Embed API**

---
##  Credits
- Built by **Team Steak House** 🍴
- Content & images: restaurant branding

---

##  License
This project is for **educational purposes** only.
Feel free to fork and customize for your own restaurant site.

**HTML:**
  - Created index.html with header, navigation, video section, popular picks, about section, gallery, and footer.
  - Added pages/about.html, pages/contact.html, pages/mune.html with respective content.
  - Implemented responsive navigation bar with links to all pages.
  - Added contact form with rating stars in contact.html.
  - Included Google Maps embed in contact page.

##  ChangeLog
##  (Part 2)  
- Removed CSS from all HTML pages (`index.html`, `contact.html`, etc.)  
- Created a CSS file called **`style.css`**  
- Linked the stylesheet in each HTML file using:  
  ```html
  <link rel="stylesheet" href="../css/style.css">
  ```  
  (for pages inside `/pages`) and  
  ```html
  <link rel="stylesheet" href="css/style.css">
  ```  
  (for `all page`)  
- Added copyright footer:  
  ```html
  <div class="copyright">
    <p>&copy; 2025 Steak House. All rights reserved.</p>
  </div>

- **CSS:**
  - Added styles in css/style.css for layout, typography, header, navigation, sections, articles, gallery, footer, forms, and responsive design.
  - Implemented gradient backgrounds, shadows, transitions, and hover effects.
  - Added styles for menu images, rating stars, and social icons.
  - Included media queries for mobile responsiveness.

---
# TODO: Make Website Responsive for Phone and Tablet

## Completed Tasks
- [x] Analyze current CSS and HTML for responsiveness issues
- [x] Add media queries for tablets (768px) and phones (480px)
- [x] Adjust grid layouts to smaller min-widths on mobile
- [x] Make iframe responsive to prevent horizontal overflow
- [x] Reduce font sizes and adjust layouts for smaller screens

## Next Steps
- [ ] Test the website on different screen sizes (phone, tablet, desktop)
- [ ] Verify no horizontal scrolling on mobile devices
- [ ] Check other pages (about.html, contact.html, mune.html) for similar issues
- [ ] If needed, apply similar responsive fixes to other pages

## 📸 Screenshots
> Respnsvieness Evidence

### mobile view
![mobile view 320px](/assests/mobile%20tablet%20desktop%20view%20respnsvieness/mobile%20320px.png)

### Tablet view
![Tablet view 768px](/assests/mobile%20tablet%20desktop%20view%20respnsvieness/tablet%20768px.png)

### Desktop view
![Desktop view 1440px](/assests/mobile%20tablet%20desktop%20view%20respnsvieness/Desktop%201440px.png)

---
##  Reference List

W3Schools. HTML Tutorial. Available at: https://www.w3schools.com/html/
 (Accessed: 4 September 2025).

W3Schools. CSS Tutorial. Available at: https://www.w3schools.com/css/
 (Accessed: 2 September 2025).

Font Awesome. Free Icons. Available at: https://fontawesome.com/icons
 (Accessed: 1 September 2025).

Google Developers. Google Maps Embed API. Available at: https://developers.google.com/maps/documentation/embed
 (Accessed: 2 September 2025).




 ## The Feedback(Part 2)

Overall Feedback
Flawless code, perfect structure, and zero bugs. Legendary work!!!
Try to improve on the skills (based on the rubric) where maximum marks were not obtained.

**I Improve this :**

1. GitHub: Project Pushed with Multiple Descriptive Commits
 Making more frequent, descriptive GitHub commits

2. Responsive Design: Media Queries/Breakpoints for Tablet and Mobile
 I Need to Improve
Add more structured media queries.
Ensure the layout adjusts cleanly on all screen sizes.
Improve spacing, font sizes, and stacking on mobile/tablet.

I  Improve
Use standard breakpoints:

 Mobile (0–480px) 
@media (max-width: 480px) { }

Tablet (481–768px) 
@media (max-width: 768px) { }


## 🔄 CHANGE LOG (Part 3)

 1. Gallery & Visual Enhancements

* Added and integrated the **Gallery Lightbox** on the **Index** and **Menu** pages.
* Renamed **all images** for better SEO, accessibility, and organisation.

 2. UI Components

* Added **Accordion** functionality:

 * Used on the **Menu** page for menu categories.
 * Used on the **Enquiry** 

 3. Automation & Functionality**

* Implemented **Auto Date and Time** feature on the **Enquiry** page.
* Added a **Search Filter** on the **Menu** page to filter items dynamically.

4. SEO & Social Media

* Added **On-page SEO** for all pages (meta tags, titles, descriptions, keywords).
* Set up and tested **social media links** (all platforms working correctly).

5. JavaScript Enhancements

* Added JavaScript validation and behaviour for:

  * Contact Form**
  * Enquiry Form**
  * Index Page**
  * Menu Page**

6. Styling Updates

* Updated and improved **CSS** for better layout, spacing, colours, and responsiveness.

7. New Pages

* Added an **Enquiry Page**, including:

  * Form structure
  * Validation
  * Auto timestamp
  * Accordion section

## 📚 Reference List

Lightbox2. Lightbox Gallery Script Documentation. Available: https://lokeshdhakar.com/projects/lightbox2/

Mozilla Developer Network (MDN). JavaScript Reference. Available: https://developer.mozilla.org/en-US/docs/Web/JavaScript

Font Awesome. Icons Reference. Available: https://fontawesome.com/icons

Google Developers. SEO Starter Guide. Available: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
