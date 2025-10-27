
# QuickShow 🎬

A modern movie booking web application built with the MERN stack (MongoDB, Express.js, React, Node.js). Book your favorite movies, select seats, and manage shows with ease.

🌐 **[Live Demo](https://quickshow-client-kohl.vercel.app/)** | [GitHub](https://github.com/PriyanshuDalakoti/QuickShow)

## Features ✨

- Browse currently playing movies
- Book tickets and select seats
- Secure payments with Stripe
- Admin dashboard to manage shows
- Email notifications for bookings
- User authentication with Clerk

## Tech Stack 🛠

- **Frontend:** React + Vite, TailwindCSS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** Clerk
- **Payments:** Stripe
- **Emails:** SMTP (Brevo)

## Setup and Installation 🚀

1. Clone the repository
```bash
git clone https://github.com/PriyanshuDalakoti/QuickShow.git
cd QuickShow
```

2. Install dependencies
```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

3. Set up environment variables

Create `.env` files in both `client` and `server` directories:

`server/.env`:
```
MONGODB_URI=your_mongodb_uri
CLERK_PUBLISHABLE_KEY=your_clerk_public_key
CLERK_SECRET_KEY=your_clerk_secret_key
TMDB_API_KEY=your_tmdb_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```

`client/.env`:
```
VITE_BASE_URL=http://localhost:3000
VITE_TMDB_IMAGE_BASE_URL=https://image.tmdb.org/t/p/original
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_public_key
```

4. Run the application

```bash
# Start the server (from server directory)
npm run server

# Start the client (from client directory in a new terminal)
npm run dev
```

The server will run on `http://localhost:3000` and the client on `http://localhost:5173`.

## Usage 📱

1. Visit the homepage to browse movies
2. Click on a movie to see show times
3. Select seats and proceed to payment
4. Receive confirmation email after successful booking

## Admin Access 👑

Access the admin dashboard at `/admin` to:
- Add new movie shows
- View all bookings
- Manage show timings

## Contributing 🤝

Contributions are welcome! Please:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## Contact 📧



## Deployment 🚀

- Frontend: [https://quickshow-client-kohl.vercel.app/](https://quickshow-client-kohl.vercel.app/)
- Backend: Deployed on Vercel
