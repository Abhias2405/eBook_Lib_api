<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logoColor=white&logo=nodedotjs&color=339933" alt="nodejs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
    <img src="https://img.shields.io/badge/-Express-black?style=for-the-badge&logoColor=white&logo=express&color=000000" alt="express" />
  </div>
  <h3 align="center">E-Book Library API</h3>
   <div align="center">
     RESTful API for E-Book management with TypeScript and MongoDB
    </div>
</div>

## 📋 Table of Contents
1. 🔋 [Features](#features)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🤸 [Quick Start](#quick-start)
4. 🚀 [API Endpoints](#endpoints)
5. 🛠️ [Environment Setup](#environment)

## <a name="features">🔋 Features</a>
👉 **Authentication**: JWT-based auth system  
👉 **Book Management**: Complete CRUD operations  
👉 **Image Handling**: Cloudinary integration  
👉 **Type Safety**: Built with TypeScript  
👉 **Cloud Deployment**: Hosted on Render.com

## <a name="tech-stack">⚙️ Tech Stack</a>
- Node.js with Express
- TypeScript
- MongoDB
- Cloudinary
- JWT Authentication

## <a name="quick-start">🤸 Quick Start</a>
```bash
git clone https://github.com/Abhias2405/eBook_Lib_api
cd eBook_Lib_api
npm install
npm run dev
```

## <a name="endpoints">🚀 API Endpoints</a>
### Books
- GET `/api/books` - Get all books
- GET `/api/books/:id` - Get single book
- POST `/api/books` - Create book
- PUT `/api/books/:id` - Update book
- DELETE `/api/books/:id` - Delete book

### Auth
- POST `/api/auth/login` - Admin login
- GET `/api/auth/profile` - Get admin profile

## <a name="environment">🛠️ Environment Setup</a>
```plaintext
PORT=
MONGO_CONNECTION_STRING=
NODE_ENV=
JWT_SECRET=
CLOUDINARY_CLOUD=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
FRONTEND_DOMAIN=
```
