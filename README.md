# Dream Nest

Dream Nest is a web application that allows users to list and book properties for short-term rentals. Users can register, log in, create listings, book properties, and manage their trips, wish lists, property listings, and reservations.

## Features

- **User Authentication**: Users can register and log in to their accounts.
- **Property Listings**: Users can create, view, and search for property listings.
- **Bookings**: Users can book properties for specific dates.
- **Trip Management**: Users can view their booked trips.
- **Wish List**: Users can add and remove properties from their wish list.
- **Host Features**: Users can become hosts and manage their property listings and reservations.

## Technologies Used

- **Frontend**: React, Redux, Material-UI, SCSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **File Upload**: Multer

## Project Structure

```
dream_nest/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Loader.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── Slide.jsx
│   │   ├── redux/
│   │   │   ├── state.js
│   │   │   ├── store.js
│   │   ├── styles/
│   │   │   ├── variables.scss
│   │   │   ├── Loader.scss
│   │   │   ├── Navbar.scss
│   │   │   ├── Slide.scss
│   │   ├── App.js
│   ├── package.json
├── server/
│   ├── models/
│   │   ├── Booking.js
│   │   ├── Listing.js
│   │   ├── User.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── booking.js
│   │   ├── listing.js
│   │   ├── user.js
│   ├── index.js
│   ├── package.json
├── README.md
```

## Setup and Running the Project

### Prerequisites

- Node.js
- MongoDB

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/smitrami-123/dream_nest.git
   cd dream_nest
   ```

2. **Setup the client:**
   ```sh
   cd client
   npm install
   npm start
   ```

3. **Setup the server:**
   ```sh
   cd server
   npm install
   ```

4. **Environment Variables:**

   Create a `.env` file in the `server` directory and add the following:

   ```
   MONGO_URL=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret>
   ```

5. **Run the server:**
   ```sh
   npm start
   ```

## Usage

- Open your browser and navigate to `http://localhost:3000` to access the client application.
- The server will be running on `http://localhost:3001`.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request for any feature requests or bug fixes.
