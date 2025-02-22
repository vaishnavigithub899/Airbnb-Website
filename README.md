# Airbnb Clone (Web-Development-Project)

## 📌 Project Overview
This is a basic minor project for understandig web deveopment concept by using these technologies (MongoDB, Express.js, Node.js, EJS). Airbnb clone that provides CRUD operations for property listings and reviews. Users can create, read, update, and delete properties while also leaving reviews.

## 🚀 Features
- **User Authentication & Authorization**
- **Property Listings & Management** (CRUD operations for properties)
- **Reviews & Ratings** (CRUD operations for reviews)


## 🛠️ Tech Stack
### Frontend:
- EJS (Embedded JavaScript Templates)
- Bootstrap (Styling)

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose ORM)

## 🔧 Installation & Setup
### Prerequisites:
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/vaishnavigithub899/Airbnb-Website.git
   cd airbnb
   ```

2. **Project Setup**
   ```sh
   cd backend
   npm airbnb
   npx nodemon  # Starts the server
   ```

3. **Frontend Setup** (EJS Templates are served via Express)
   No additional setup needed for frontend as EJS is rendered from the backend.

4. **Environment Variables**
   Create a `.env` file in the backend folder with the following:
   ```env
   MONGO_URI=your_mongodb_uri
   CLOUDINARY_URL=your_cloudinary_url
   ```

## 🔄 API Endpoints
| Method | Endpoint               | Description                   |
|--------|------------------------|-------------------------------|
| POST   | `/api/auth/signup`   | Register new user             |
| POST   | `/api/auth/login`      | Login user                    |
| GET    | `/api/listings`      | Get all property listings     |
| POST   | `/api/listings`      | Add a new property            |
| PUT    | `/api/listings/:id`  | Update property details       |
| DELETE | `/api/listings/:id`  | Delete a property             |
| GET    | `/api/reviews`         | Get all reviews               |
| POST   | `/api/reviews`         | Add a review                  |
| PUT    | `/api/reviews/:id`     | Update a review               |
| DELETE | `/api/reviews/:id`     | Delete a review               |


## 👨‍💻 Contributor
- [@vaishnavijha](https://github.com/vaishnavigithub899)

## 💬 Feedback
If you have any suggestions or issues, feel free to open an issue in this repository!







