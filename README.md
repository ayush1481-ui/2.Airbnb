# 🏡 Airbnb- Your Next Stay, Simplified.

**This Airbnb** is a full-stack MERN application designed to showcase modern web development practices. Discover, list, and book unique properties with ease, all built on a robust and scalable architecture.

---

## ✨ Features

* **🔐 Seamless User Authentication:** Secure Login and Registration powered by JSON Web Tokens (JWT).
* **🏡 Dynamic Listing Management:**
    * Create, view, and manage your property listings.
    * Detailed listing pages with descriptions, amenities, and more.
* **📅 Intuitive Booking System:**
    * Book properties with a user-friendly date picker.
    * View your complete booking history.
* **☁️ Cloud-Powered Image Uploads:** Effortlessly upload property images using Cloudinary.
* **💻 Fully Responsive Design:** Enjoy a consistent experience across all devices, thanks to Tailwind CSS.
* **🔗 Client-Side Routing:** Smooth navigation with React Router DOM.

---

## 🚀 Technologies

* **Frontend:**
    * **React.js:** Modern JavaScript library for building user interfaces.
    * **React Router DOM:** Declarative routing for React.
    * **Tailwind CSS:** Utility-first CSS framework for rapid UI development.
    * **Other React Libraries:** (Add specific names if they are significant, e.g., `react-datepicker`, `axios`, etc.)
* **Backend:**
    * **Node.js:** JavaScript runtime for server-side logic.
    * **Express.js:** Fast, unopinionated, minimalist web framework for Node.js.
    * **MongoDB:** NoSQL database for flexible data storage.
    * **Mongoose:** MongoDB object data modeling (ODM) for Node.js.
    * **JSON Web Token (JWT):** For secure authentication.
    * **CORS:** Enabling cross-origin resource sharing.
    * **Cookie Parser:** Parse Cookie header and populate `req.cookies`.
* **Deployment:**
    * **Cloudinary:** For efficient image hosting and delivery.
      

---

## 📦 How to Run Locally

Get this Airbnb Project up and running on your machine in a few simple steps!

1.  **Clone the Repository:**
    ```bash
    git clone <https://github.com/ayush1481-ui/2.Airbnb.git>
    cd airbnb-clone # Or whatever your project folder is named
    ```
2.  **Install Dependencies:**
    ```bash
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```
3.  **Set Up Environment Variables:**
    Create a **`.env`** file in your **`backend`** directory with the following:
    ```
    MONGO_URL="YOUR_MONGODB_CONNECTION_STRING"
    JWT_SECRET="YOUR_JWT_SECRET_KEY"
    CLOUDINARY_CLOUD_NAME="YOUR_CLOUD_NAME"
    CLOUDINARY_API_KEY="YOUR_API_KEY"
    CLOUDINARY_API_SECRET="YOUR_API_SECRET"
    ```
    *Replace placeholders with your actual credentials.*

4.  **Start the Servers:**
    ```bash
    # In one terminal, start the backend server
    cd backend
    npm start

    # In another terminal, start the frontend development server
    cd frontend
    npm start
    ```

5.  **Access the Application:**
    Open your browser and navigate to `http://localhost:3000` (or whatever port your React app runs on).

---

## 💡 Learnings & Future Enhancements

This project allowed me to deepen my understanding of full-stack MERN development, focusing on secure authentication, efficient data management with MongoDB, and creating a dynamic, responsive user experience.

**Future plans include:**

* Adding a search and filtering functionality for listings.
* Implementing a messaging system between users.
* Integrating payment gateway for real bookings.

---
