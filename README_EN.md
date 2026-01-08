🇫🇷 [French version available here](README.md)

# Cinema Club 108 - Product Page

## Description

This web page presents the structure of a product page for an online store dedicated to a cinema called Club 108.  
It displays news, showtimes, programming, as well as practical information about the cinema.

---


## Main Content

- **Header:** logo, title, and main navigation menu with links to different site sections.  
- **Main:**  
  - A featured news item with image and text  
  - A table of scheduled showtimes  
  - Cinema address with structured data (Schema.org)  
  - A publication with image and action button  
  - A "This Week" section presenting several events with images  
- **Footer:** useful links and cinema logo

---

## Technologies Used

- Semantic HTML5  
- Schema.org Microdata for semantic markup of address data  
- ARIA attributes for accessibility  
- Responsive design with `srcset` and `sizes` for images  
- External CSS (`default.css` and `style.css`) for styling

---

## File Organization

/devoir-05/
├── css/
│ ├── default.css
│ └── style.css
├── img/
│ ├── logo.png
│ ├── cinema1000.webp
│ ├── cinema2.webp
│ ├── theatre2.webp
│ └── fauteuils.webp
├── index.html (main page)
└── README.md (this file)

---

## Instructions

- Open `index.html` in a modern browser to view the page.  
- Modify HTML content as needed (titles, images, text, schedules).  
- Adjust CSS styles in linked files to customize appearance.

---

## Accessibility

- Main navigation and footer are accessible via ARIA attributes.  
- Images include descriptive alt attributes.  
- Use of semantic tags improves screen reader comprehension.

---

## Possible Improvements

- Add a real functional booking system.  
- Dynamically update schedules and showtimes via JavaScript or backend.  
- Optimize performance with lazy loading of images.  
- Add a functional contact form.  
- Extend microdata to better reference movies and events.

---

## Author

Vanessa PAGANOTTO

---

## License

This project is licensed under the MIT License.
