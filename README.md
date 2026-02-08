# SgHawkerHub 🍲

> A responsive web application helping patrons find hawker stalls and allowing NEA officers to log hygiene inspections.

![Responsive Design](https://img.shields.io/badge/Design-Responsive-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 🔗 Live Deployment
**View the live project here:** [INSERT YOUR GITHUB PAGES LINK HERE e.g., https://username.github.io/SgHawkerHub]

---

## 📖 Project Overview
**SgHawkerHub** is designed to streamline the hawker centre experience in Singapore. It serves three distinct user groups:
1.  **Patrons:** To discover food, manage orders, and view hygiene grades.
2.  **Stall Owners (Vendors):** To manage menus, track sales, and handle orders.
3.  **NEA Officers:** To conduct and log hygiene inspections efficiently.

This project was built Mobile-First to ensure accessibility for users on the go.

---

## 👥 Team & Individual Contributions
| Student ID | Name | Role / Key Features Developed |
| :--- | :--- | :--- |
| **10272535K** | **Jonathan Choo** | • **Ordering System:** Menu Page, Cart & Checkout flow, Order History.<br>• **UI/UX:** Dark Mode, Global NavBar, Overall UI consistency.<br>• **API:** Time API integration for Orders & SmartTableFinder. |
| **S10272790E** | **Koh Jun Wen** | • **Vendor Administration:** Vendor Profile, Rental Bill Management.<br>• **Menu Control:** Add/Edit/Remove Menu items.<br>• **Engagement:** Customer Feedback viewing, Eco-friendly initiatives page. |
| **S10272093E** | **Darren Yap** | • **NEA Officer Features:** Officer Dashboard, Inspection Logging Page, Food Safety Protocols.<br>• **Finder Tools:** Live Table Finder, Smart Food Finder. |
| **S10275499K** | **Chop Wei Jie** | • **Vendor Dashboard:** Daily Sales Calculation, Goal Tracker, Sales Trend (7-Day Chart).<br>• **Workflow:** Order Workflow Management, Vendor Feedback Reply.<br>• **Auth:** Multi-role Authentication Page (Login/Sign Up). |
| **S10275457K** | **Thaariq Akbar** | • **Core Infrastructure:** Firebase Setup & Database Seeding (Hawker/Stall Data).<br>• **User Mgmt:** Login/Sign-up Logic, Edit Profile (Account Page).<br>• **Landing:** Home Page implementation. |

---

## 🛠️ Technologies Used
### Core Stack
* **HTML5:** Semantic structure for accessibility.
* **CSS3:** Custom styling, Flexbox/Grid for responsive layout.
* **JavaScript (ES6+):** DOM manipulation and logic.

### Frameworks & Libraries
* **FontAwesome:** Used for scalable vector icons (Nav bars, action buttons).
* **Google Fonts:** Used to ensure typography consistency across devices.
* **Chart.js:** *[Used by Wei Jie]* To render the 7-Day Sales Trend visualization for Vendors.
* **Firebase:** *[Used by Thaariq]* For user authentication and real-time database storage.

### APIs
* **[INSERT API NAME HERE]:** Used for [e.g., retrieving live weather data].
* **WorldTimeAPI:** *[Used by Jonathan]* To verify order timestamps and table availability.

---

## 🧪 Testing & Credentials
To test the application, please use the following credentials for the different user roles:

| Role | Username / Email | Password |
| :--- | :--- | :--- |
| **Patron** | `patron@test.com` | `password123` |
| **Vendor** | `vendor@test.com` | `password123` |
| **NEA Officer** | `officer@test.com` | `password123` |

### Testing Protocol
* [cite_start]**Responsiveness:** Tested on iPhone X, iPad Pro, and Desktop resolutions using Chrome DevTools[cite: 836].
* [cite_start]**Validation:** HTML and CSS validated via W3C Validator[cite: 732].
* **Lighthouse:** Audited for Performance and Accessibility.

---

## 🤖 AI Assistance Declaration
Generative AI (ChatGPT/Gemini) was used as an assistive tool for debugging and code optimization.

* **Query 1:** *[Insert screenshot of query here, e.g., "How to sort JSON array by date in JS"]*
    * *Application:* Used in the Order History page to sort past orders.
* **Query 2:** *[Insert screenshot or description]*
    * *Application:* Used to debug the Firebase connection issue on the Login page.

---

## 📂 Deployment
1.  Clone the repository: `git clone https://github.com/[username]/SgHawkerHub.git`
2.  Navigate to the folder.
3.  Open `index.html` in your browser (or use Live Server in VS Code).
4.  **Note:** An active internet connection is required for Firebase and API features.

---

## © Credits
* **Images:** Unsplash, Pexels.
* **Icons:** FontAwesome.
* **Reference Logic:** MDN Web Docs for LocalStorage implementation.
