# TripAlly

TripAlly is a travel companion web application built using the MERN (MongoDB, Express.js, React, Node.js) stack. It provides users with a seamless experience to plan, explore, and manage their trips efficiently.

**Live Demo:** [trip-ally.vercel.app](https://trip-ally.vercel.app/)

## 🚀 Features

- **User Authentication** — Secure login/signup using JWT authentication.
- **Trip Planning** — Users can create and manage travel itineraries.
- **Interactive Maps** — Integration with Google Maps for location-based features.
- **Accommodation & Transport Booking** — Find and book stays and transport options.
- **Community & Reviews** — Users can share their travel experiences and leave reviews.
- **Responsive UI** — A modern, mobile-friendly interface designed with React and Tailwind CSS.

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js (Vite) + Tailwind CSS |
| Backend | Node.js + Express.js |
| Database | MongoDB + Mongoose |
| Authentication | JSON Web Tokens (JWT) |
| Maps API | Google Maps API |
| State Management | React Context API / Redux (if applicable) |

## 📂 Folder Structure

```
TripAlly
│── frontend   # React.js frontend
│── backend    # Node.js & Express backend
```

## 📂 Project Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Rohs21/TripAlly.git
cd TripAlly
```

### 2️⃣ Install Dependencies

```bash
# Install server dependencies
cd backend
npm install

# Install client dependencies
cd ../frontend
npm install
```

### 3️⃣ Environment Variables

Create a `.env` file in the `backend` directory and add the required credentials:

```
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
MAPS_API_KEY=your-google-maps-api-key
```

### 4️⃣ Run the Application

```bash
# Start backend
cd backend
npm run dev

# Start frontend
cd ../frontend
npm run dev
```

## 🛠 Contributing

Feel free to contribute! Fork the repository, make your changes, and submit a PR. 🎉

## 📄 License

Add a license (e.g. MIT) here if you'd like others to know how they can use this project.
