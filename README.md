# RealTime Chat Application

A Real-time Chat application built with Node.js, Express, MongoDB, and Cloudinary. We can say it's a WhatsApp Clone but this app doesn't have features to share status or make calls unlike in WhatsApp. 

## Features

- Real-time chat functionality
- JWT-based authentication
- Cloudinary integration for image uploads
- Environment-based configuration

---

## 🛠 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Santhusha-bit/Realtime-ChatApp
cd Realtime-ChatApp
````

## 2. Environment Variables ⚙ 

Create a `.env` file in the root directory and configure it with the following values:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

> **Note**: Replace all placeholder values (e.g., `your_mongodb_connection_string`) with your actual credentials.

## 3. Build the App 🚧

To create a production build:

```bash
npm run build
```

## 4. Start the App 🚀

To start the server:

```bash
npm start
```

