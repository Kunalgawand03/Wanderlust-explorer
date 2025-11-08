# Wanderlust Explorer 🌍

**Wanderlust Explorer** is a full-stack web application where users can explore, create, and review travel listings. Built with Node.js, Express, MongoDB, and EJS, it offers a seamless user experience for travelers and listing owners alike. Users can sign up, log in, create listings with images, leave reviews, and manage their content.  

---

## ✨ Features

- **User Authentication:** Secure signup and login using Passport.js.
- **Listings:** Create, read, update, and delete travel listings.
- **Image Uploads:** Upload images for listings using Cloudinary.
- **Reviews:** Users can add reviews to listings and manage their reviews.
- **Flash Messages:** Provides instant feedback with success and error messages.
- **Search by Category:** Filter listings by categories.
- **Responsive UI:** Mobile-friendly and visually appealing interface with EJS templates.

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas or local)
- **Authentication:** Passport.js (Local Strategy)
- **File Uploads:** Multer & Cloudinary
- **Templating:** EJS with ejs-mate
- **Styling:** CSS (custom)
- **Session Management:** express-session with connect-mongo
- **Validation:** Joi for schema validation

---

## 📂 Project Structure

├── Models
│ ├── listing.js
│ ├── review.js
│ └── user.js
├── public
│ ├── css
│ └── js
├── routes
├── utils
│ ├── ExpressError.js
│ └── wrapAsync.js
├── views
│ ├── includes
│ ├── layouts
│ ├── listings
│ └── users
├── cloudConfig.js
├── schema.js
├── app.js
├── package.json
└── README.md

yaml
Copy code

---

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Wanderlust-Explorer.git
cd Wanderlust-Explorer
Install dependencies:

bash
Copy code
npm install
Create a .env file in the root:

env
Copy code
NODE_ENV=development
SECRET=your_session_secret
ATLASDB_URL=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
Start the server:

bash
Copy code
npm start
Open in your browser:

arduino
Copy code
http://localhost:8080
💻 Usage
Visit /signup to create an account.

Visit /login to log in.

Create new listings under /listings/new.

Explore listings at /listings.

Add reviews to listings.

Edit or delete your listings/reviews.

💡 Future Enhancements
-Add search by location and price.
-User profile page with all listings and reviews.
-Pagination and infinite scroll for listings.
-Social login (Google, Facebook).
