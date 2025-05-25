# 🔗 LinkUp – MERN Social Media App

**LinkUp** is a full-stack social media application built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It enables users to connect with others, share posts, like/comment, manage their profiles, and more — all within a clean and responsive interface.

---

## 🚀 Features

- 🔐 User Authentication (Register/Login)
- 📝 Create, Edit & Delete Posts
- ❤️ Like & 💬 Comment on Posts
- 👤 View & Update Profiles
- ➕ Follow/Unfollow Users
- 🛠️ Admin Panel for user management
- 🧾 Real-time Notifications
- 🌐 Fully Responsive Design
- ☁️ Image Uploads via Cloudinary

---

## 🖼️ Screenshots

### Home Feed
![Image](https://github.com/user-attachments/assets/8f9bb264-bdcd-4393-be3d-1b71de9a59c1)

### Login Page

![Image](https://github.com/user-attachments/assets/851a23f9-599c-469d-be99-8aafac887933)

![Image](https://github.com/user-attachments/assets/70d81a77-b6f0-434b-9aaf-4458090746b9)


### SignUp Page

![Image](https://github.com/user-attachments/assets/fbf7d6b2-eeb0-4a73-a71b-172fb8574961)
![Image](https://github.com/user-attachments/assets/33bda02b-1278-4d1d-b1ff-c58991e5a536)

![Image](https://github.com/user-attachments/assets/851a23f9-599c-469d-be99-8aafac887933)

### 👤 Profile Page

![Image](https://github.com/user-attachments/assets/b7f1d838-21d0-4517-9d52-a7ba6374b437)

### 📝 Create Post

![Image](https://github.com/user-attachments/assets/514f0656-058b-4380-87c3-6606a0f38a48)

### Post comment

![Image](https://github.com/user-attachments/assets/17452367-4721-4113-9009-95b4255bd8cc)

![Image](https://github.com/user-attachments/assets/663e0546-71af-432f-a5ce-5e8d3afc5ff0)


---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose

### Others
- JWT for Authentication
- Cloudinary for Image Hosting
- Docker & Docker Compose
- Axios, React Router, etc.

---

## ⚙️ Local Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/PendemLikhitha/LinkUp-MERNSocialMediaPlatform.git
cd LinkUp-MERNSocialMediaPlatform

## 2️⃣ Install Dependencies

### 🔧 Backend

```bash
cd server
npm install

Frontend

cd ../client
npm install

3️⃣ Add .env Files
Create .env in both server/ and client/ directories.

📄 Example .env (Server)
env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

4️⃣ Start the App
▶️ In one terminal (backend):
cd server
npm install
node server.js
▶️ In another terminal (frontend):
cd client
npm start
🔗 Open http://localhost:3000 to view the app in your browser.
Made with ❤️ using the MERN Stack.

