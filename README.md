# 🌍 Countries Explorer

A modern and responsive web application that allows users to explore countries around the world using real-time data from the REST Countries API.

🔗 **Live Demo:** https://countries-appvansh.netlify.app/

---

## 🚀 Features

- 🌎 View all countries from the REST Countries API
- 🔍 Search countries by name
- 🌍 Filter countries by region
- 🏳️ Display country flags
- 📊 View detailed country information:
  - Native Name
  - Population
  - Region
  - Sub Region
  - Capital
  - Top Level Domain
  - Currencies
  - Languages
  - Border Countries
- 🌙 Dark Mode / Light Mode Toggle
- 📱 Fully Responsive Design
- ⚡ Fast API-based Data Fetching
- 🔗 Navigation between country list and country details page

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)

### API
- REST Countries API

### Deployment
- Netlify

---

## 📂 Project Structure

```bash
countries-app/
│
├── index.html
├── country.html
│
├── style.css
├── country.css
│
├── script.js
├── country.js
│
└── README.md
```

---

## 📸 Screenshots

### Home Page

<img width="100%" alt="Home Page" src="https://via.placeholder.com/1200x600?text=Countries+Explorer+Home">

### Country Details Page

<img width="100%" alt="Country Details" src="https://via.placeholder.com/1200x600?text=Country+Details+Page">

> Replace the placeholders with actual screenshots of your project.

---

## ⚙️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/VanshChhabra0706/countries-app.git
```

### Navigate to Project Folder

```bash
cd countries-app
```

### Run Locally

Simply open:

```bash
index.html
```

or use VS Code Live Server.

---

## 🌐 API Used

REST Countries API

```http
https://restcountries.com/v3.1/all
```

### Data Fetched

- Country Name
- Flag
- Population
- Region
- Capital
- Languages
- Currencies
- Native Name
- Borders
- Top-Level Domains

---

## 🔍 Search Functionality

Users can search countries instantly using:

```javascript
country.name.common
  .toLowerCase()
  .includes(searchValue.toLowerCase())
```

This provides a case-insensitive search experience.

---

## 🌎 Region Filter

Countries can be filtered by:

- Africa
- Americas
- Asia
- Europe
- Oceania

The application dynamically updates the displayed countries based on the selected region.

---

## 🌙 Dark Mode

Dark mode is implemented using CSS custom properties and JavaScript.

```javascript
document.body.classList.toggle('dark')
```

The theme switches instantly while maintaining a clean UI experience.

---

## 📱 Responsive Design

The application is fully responsive and optimized for:

- Desktop
- Laptop
- Tablet
- Mobile Devices

CSS Flexbox and responsive layouts are used to ensure a seamless experience across all screen sizes.

---

## 🚀 Deployment

This project is deployed on Netlify.

### Live Website

👉 https://countries-appvansh.netlify.app/

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Working with REST APIs
- Fetch API and Promises
- DOM Manipulation
- Event Handling
- Dynamic Rendering
- URLSearchParams
- JavaScript Array Methods
  - map()
  - filter()
  - forEach()
  - Object.values()
- Responsive Web Design
- Dark Mode Implementation
- Git & GitHub Workflow
- Netlify Deployment

---

## 🔮 Future Improvements

- Add Loading Skeletons
- Add Pagination
- Add Infinite Scrolling
- Improve Search Performance
- Add Country Comparison Feature
- Store Theme Preference in Local Storage
- Add Favorites/Bookmarks

---

## 👨‍💻 Author

### Vansh Chhabra

GitHub:
https://github.com/VanshChhabra0706


---

## ⭐ Support

If you found this project helpful, consider giving it a star ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute it for learning and personal projects.
