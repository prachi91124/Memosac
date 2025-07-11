# 📸 Memosac – A Digital Heirloom Vault

**Memosac** is a secure and modern web application that serves as a **digital heirloom vault** — allowing users to store, organize, and preserve digital memories such as photos, notes, recipes, and time capsules. Designed with privacy, security, and user-friendliness in mind, Memosaac offers features like scheduled memory delivery and media galleries to create a long-lasting digital legacy.

---

## 🎯 Project Objective

The digital world often lacks a secure, personalized platform to preserve important digital memories for future generations. Memosac solves this by enabling users to store, organize, and share their digital legacies securely and meaningfully, with features such as:

- Secure Time Capsules  
- Media Galleries & Albums  
- Digital Recipe Boards  
- Encrypted Storage & JWT-authenticated access

---

## 🌟 Key Features

- 🔐 **JWT & OAuth2 Authentication** – for secure and personalized access  
- ☁️ **AWS S3 + GridFS Storage** – for efficient, scalable file management  
- 🧳 **Time Capsule Module** – schedule digital memories to be released in the future  
- 🖼️ **Albums & Gallery** – organize and view media in an elegant, responsive layout  
- 📒 **Posts & Recipes** – create personal stories or save your favorite recipes  
- 🐳 **Dockerized App** – containerized for seamless development & deployment  
- 📈 **Fully Scalable** – built with modular architecture and cloud-ready design

---

## 🧠 Concept in Detail

Memosac is more than a media library — it's a **digital legacy manager**. Whether it's a photo album for your family, a private recipe collection, or a set of heartfelt notes scheduled for delivery years later, Memosaac is designed to be your trusted memory vault.

The highlight feature, **Time Capsules**, lets users upload files or messages and schedule them for future access — perfect for birthdays, anniversaries, or personal milestones.

---

## 🛠️ Tech Stack

| Layer       | Technologies Used                                       |
|-------------|----------------------------------------------------------|
| **Frontend** | React.js, Custom CSS                                    |
| **Backend**  | Node.js, Express.js                                     |
| **Database** | MongoDB + Mongoose, GridFS                              |
| **Storage**  | AWS S3, Multer                                          |
| **Auth**     | JWT, Google OAuth2.0                                    |
| **DevOps**   | Git, Docker, Nginx, .env Config, GitHub Actions (optional) |

---

## 🧪 Testing & Validation

✔️ Authentication with JWT & Google OAuth  
✔️ File Uploads to AWS S3 & GridFS  
✔️ Time Capsule scheduling and delivery  
✔️ Responsive UI for Gallery/Album  
✔️ Modular API routes for Posts, Recipes, and Media  
✔️ Dockerized environments for dev & production  

---

## 🚀 Running the App

### ⚙️ Prerequisites
- Node.js ≥ v16  
- MongoDB Atlas or local instance  
- AWS S3 Bucket & Keys  
- Docker (optional but recommended)

### 🔧 Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/yourusername/memosaac.git
cd memosaac
```
Set up environment variables:
```bash
cp .env.example .env
# Add Mongo URI, AWS keys, JWT_SECRET, and OAuth credentials
```

Start Backend:
```bash
cd server
npm install
npm start
```
Start Frontend:

```bash
cd client
npm install
npm start
```
# 🧑‍🤝‍🧑 Meet the Team
## 👩‍💻 [Pearl (Lead Developer)](https://github.com/perkyPearl)
- Integrated Google OAuth for seamless login

- Managed AWS S3 file storage and Time Capsule system

- Dockerized the platform for consistent deployment

- Led debugging and core system integration

## 👩‍🎨 Prachi Anand
- Designed Album & Gallery with responsive UI

- Integrated GridFS for handling large media

- Enhanced file upload flow using Multer

- Improved frontend performance and stability

## 👩‍🍳 [Prachi Malik](https://github.com/prachimalik661)
- Designed robust MongoDB schemas

- Developed Posts & Recipes modules

- Optimized data models for content-heavy modules

## 👨‍💻 [Guransh Singh](https://github.com/Guranshsingh5911)
- Implemented authentication and session security

- Handled profile management, login, and logout flows

- Ensured API security and access control

- Optimized frontend rendering and real-time data logic

# 🔮 Future Scope
- 📱 Develop mobile app version

- 🛡️ Add Multi-Factor Authentication (MFA)

- 🗃️ File versioning, bulk upload & better organization

- 🖼️ Album category tagging and filter system

# 📚 References
- MongoDB

- React

- AWS S3

- OAuth 2.0

- Docker

- GitHub Copilot

# 📬 Contact
## Made with 💙 by Team Memosac
### [LinkedIn](linkedin.com/in/perkypearl) – Pearl 👾 
### [LinkedIn](www.linkedin.com/in/prachi9124) – Prachi Anand 💀
### [LinkedIn](linkedin.com/in/prachi-malik-313743282) – Prachi Malik 🕷️
### [LinkedIn](linkedin.com/in/guransh-singh-336b4a254) – Guransh Singh 🏎️

