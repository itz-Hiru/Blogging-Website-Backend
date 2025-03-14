![Blogging Backend](https://img.shields.io/badge/Blogging%20Backend-Node.js,%20Express,%20Firebase,%20AWS,%20MongoDB-blue?style=for-the-badge&logo=node.js)

# 🚀 Blogging Website Backend

```ascii
  ____  _              _      _     _                     _     _            
 |  _ \| | ___   ___  | |    (_)___| |_   ___  __ _  __ _| |__ | | ___  ___  
 | |_) | |/ _ \ / _ \ | |    | / __| __| / __|/ _` |/ _` | '_ \| |/ _ \/ __| 
 |  __/| | (_) | (_) || |____| \__ \ |_  \__ \ (_| | (_| | |_) | |  __/\__ \ 
 |_|   |_|\___/ \___(_)______|_|___/\__| |___/\__,_|\__,_|_.__/|_|\___||___/
```

## 🌟 Features

- 📝 **RESTful API** with Express.js
- 🔥 **Firebase Authentication** for secure login
- 🗄 **MongoDB** for scalable NoSQL data storage
- ☁️ **AWS S3** for media storage
- 🚀 **Optimized Performance** with caching & rate-limiting
- 📈 **Analytics Integration** to track user engagement
- 🔄 **JWT Authentication** for user sessions
- 🛡️ **Security** with Helmet and CORS

## 🏗️ Tech Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)  
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)  
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white)  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)  
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)  

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/itz-Hiru/Blogging-Website-Backend.git
cd Blogging-Website-Backend

# Install dependencies
npm install
```

## 🚀 Usage

```bash
# Start development server
npm start
```

## 🛠️ API Endpoints

| Method | Endpoint           | Description                 |
|--------|-------------------|-----------------------------|
| GET    | /api/posts        | Fetch all blog posts       |
| POST   | /api/posts        | Create a new post          |
| GET    | /api/posts/:id    | Get a single post by ID    |
| PUT    | /api/posts/:id    | Update a post             |
| DELETE | /api/posts/:id    | Delete a post             |
| POST   | /api/auth/signup  | Register a new user       |
| POST   | /api/auth/login   | Authenticate user         |
| POST   | /api/comments     | Add a comment to a post   |
| GET    | /api/comments/:id | Fetch comments for a post |

## 🔑 Environment Variables

### MongoDB and AWS data

Create a `.env` file in the root directory and add:

```ini
DB_LOCATION= mongodb location
SECRET_ACCESS_KEY= mongodb access key
AWS_SECRET_ACCESS_KEY= your aws secret key
AWS_ACCESS_KEY= your aws access key
AWS_BUCKET_NAME= your aws bucket name
AWS_BUCKET_REGION= your aws bucket region
AWS_SDK_JS_SUPPRESS_MAINTENANCE_MODE_MESSAGE = '1'
```

### Firebase data

Create a `blog-web-site-90d69-firebase-adminsdk-w0s25-443e6a3f20.json` file in the root directory and add:

```ini
{
  "type": "",
  "project_id": "",
  "private_key_id": "",
  "private_key": "",
  "client_email": "",
  "client_id": "",
  "auth_uri": "",
  "token_uri": "",
  "auth_provider_x509_cert_url": "",
  "client_x509_cert_url": "",
  "universe_domain": ""
}
```

## 🏗️ Folder Structure

```
/blogging-backend
│── Schema/
│   ├── Blog.js
│   ├── Comment.js
│   ├── Notification.js
│   ├── User.js
│── .env
│── package.json
│── blog-web-site-90d69-firebase-adminsdk-w0s25-443e6a3f20.json
│── server.js
│── README.md
```

## 🛡️ Security Practices

- ✅ **CORS Configuration** to allow only trusted origins
- ✅ **Encrypted Passwords** with bcrypt.js

## 📜 License

This project is licensed under the MIT License.

---
🚀 Happy Coding! 🎉
