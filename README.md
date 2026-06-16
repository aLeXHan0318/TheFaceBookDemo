# TheFaceBook

*A Retro Social Network Web App — Grade 10 Computer Science Final Project*

> ⚠️ **Disclaimer**
>
> This project is a school assignment created for educational purposes only.
> It is not affiliated with, endorsed by, or associated with Meta Platforms, Inc. or Facebook in any way.
> No commercial use is intended.

---

## 📖 About

**TheFaceBook** is a retro-inspired social networking web application that recreates the experience of early 2000s social media platforms while demonstrating core front-end web development concepts.

The project includes user registration, login functionality, profile management, profile picture uploads, and local data persistence using browser storage. It was developed entirely with vanilla HTML, CSS, and JavaScript as the final project for a Grade 10 Computer Science course.

The goal of this project was to strengthen my understanding of web development fundamentals without relying on external frameworks or libraries.

---

## ✨ Features

| Feature                    | Description                                                           |
| -------------------------- | --------------------------------------------------------------------- |
| 🔐 User Registration       | Create an account with name, email, password, and relationship status |
| 🔑 User Login              | Log into an existing account                                          |
| 👤 User Profile            | View and manage personal information                                  |
| 🖼️ Profile Picture Upload | Upload, preview, and remove profile pictures                          |
| 🔍 Search Interface        | Basic search UI implementation                                        |
| 📑 FAQ Page                | 18 frequently asked questions with navigation links                   |
| 📱 Responsive Layout       | CSS Grid and Flexbox-based responsive design                          |
| 💾 Local Storage           | Persistent user data stored in browser LocalStorage                   |

---

## 🛠️ Tech Stack

### Front-End

* HTML5
* CSS3
* JavaScript (Vanilla)

### Concepts Used

* Semantic HTML Structure
* CSS Grid
* Flexbox
* Responsive Design
* Form Validation
* DOM Manipulation
* LocalStorage API
* Client-Side State Management

### Frameworks

None — built completely from scratch to demonstrate fundamental web development skills.

---

## 📸 Screenshots

### Welcome Page

*<img width="1911" height="1064" alt="image" src="https://github.com/user-attachments/assets/12ce7fc1-ec2b-4c0c-8352-dff5cbec3d83" />*


### Registration Page

*<img width="1903" height="911" alt="image" src="https://github.com/user-attachments/assets/fd8cb1e2-cb59-49b5-b7c1-18e1e268eb8d" />*

### User Profile

*<img width="1876" height="891" alt="image" src="https://github.com/user-attachments/assets/9bc7a670-db2d-46e6-8da9-d12fd9bea001" />*

### FAQ Page

*<img width="1909" height="1070" alt="image" src="https://github.com/user-attachments/assets/9b2f6cf3-f622-4224-a51f-b04eb3916b9a" />*

---

## 🚀 Getting Started

### Run Locally

1. Download or clone the repository

```bash
git clone https://github.com/aLeXHan0318/The-Face-Book-Demo.git
```

2. Open the project folder

3. Launch:

```text
welcomePage.html
```

using any modern web browser.

4. Register a new account and begin exploring the application.

---

## 📁 Project Structure

```text
TheFaceBook/
│
├── welcomePage.html
├── registerPage.html
├── loginPage.html
├── HomePage.html
├── userProfile.html
├── aboutPage.html
├── faqPage.html
├── 404NotFound.html
│
├── style.css
│
└── images/
    └── default-profile.png
```

---

## 🎯 Challenges & Solutions

### Challenge 1: Managing User Data Without a Backend

Since this project does not use a server or database, user information needed to persist between page refreshes.

**Solution:**
Used the browser's LocalStorage API to save and retrieve user data.

---

### Challenge 2: Maintaining Consistent Styling

As the number of pages increased, keeping the design consistent became more difficult.

**Solution:**
Created a shared stylesheet and reusable CSS variables using `:root`.

---

### Challenge 3: Profile Picture Storage

Images needed to be stored without a backend service.

**Solution:**
Converted uploaded images into Base64 data URLs and stored them in LocalStorage.

---

## 📚 What I Learned

Through this project I learned:

* How multi-page websites are structured
* How user authentication flows work at a basic level
* How to use JavaScript to manipulate the DOM
* How browser storage can simulate persistent data
* How responsive layouts are built using Grid and Flexbox
* How to organize larger projects into maintainable files and components
* How to document software projects professionally using Markdown

---

## ⚠️ Limitations

This project is intended for educational purposes and has several limitations:

* No backend server
* No database
* No real authentication security
* No real-time messaging
* No multi-user synchronization
* Data is stored only in the user's browser

---

## 🔮 Future Improvements

Potential future features include:

* Backend integration
* Database support
* Friend system
* News feed functionality
* Posts and comments
* Real search functionality
* User-to-user messaging
* Mobile-first redesign

---

## 👨‍💻 Author

**Alex Han**

Grade 10 Computer Science Student

Project completed in 2026.

---

## 📜 License

Educational Use Only

This project was created as a school assignment and is not intended for commercial use.
