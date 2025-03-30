# Wanderlust 🌎

A modern full-stack web application for travel enthusiasts to discover, share, and review travel destinations and experiences.

## Features ✨

- **User Authentication**: Secure signup and login functionality
- **Destination Listings**: Create, view, edit, and delete travel destinations
- **Review System**: Users can leave reviews and ratings for destinations
- **Image Upload**: Support for multiple image uploads for destinations
- **Interactive Maps**: Location-based destination discovery
- **Responsive Design**: Seamless experience across all devices

## Tech Stack 🛠️

- **Frontend**:
  - HTML5, CSS3, JavaScript
  - Bootstrap for responsive design
  - EJS for templating

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB for database
  - Mongoose ODM

- **Authentication**:
  - Passport.js
  - bcrypt for password hashing

- **Cloud Services**:
  - Cloudinary for image storage
  - MongoDB Atlas for database hosting

## Installation 📥

1. Clone the repository
```bash
git clone https://github.com/sahilmadaan048/Wanderlust.git
cd Wanderlust
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
PORT=3000
MONGODB_URI=your_mongodb_uri
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

4. Start the development server
```bash
npm start
```

## Usage 💡

1. Register a new account or login with existing credentials
2. Browse destinations or create your own listing
3. Add reviews and ratings to destinations
4. Upload images to showcase destinations
5. Explore destinations on the interactive map

## API Endpoints 🔗

### Authentication
- `POST /auth/register` - Register new user
- `POST /auth/login` - Login user
- `GET /auth/logout` - Logout user

### Destinations
- `GET /destinations` - Get all destinations
- `POST /destinations` - Create new destination
- `GET /destinations/:id` - Get specific destination
- `PUT /destinations/:id` - Update destination
- `DELETE /destinations/:id` - Delete destination

### Reviews
- `POST /destinations/:id/reviews` - Add review
- `DELETE /destinations/:id/reviews/:reviewId` - Delete review

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
