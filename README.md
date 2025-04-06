# Hostel Hub - Server Side

🖥️ **Live Server:** [https://hostel-hub-server-six.vercel.app](https://hostel-hub-server-six.vercel.app)

---

## 🛠️ Features:

1. User Authentication using **JWT** (JSON Web Tokens).
2. **Role-based access control** for Admins and Users.
3. RESTful APIs using **Express.js**.
4. **MongoDB** database connection with environment-based credentials.
5. **Stripe Payment Integration** for premium package purchases.
6. Secure meal request and review handling.
7. Middleware for **JWT verification** and **Admin-only route protection**.
8. Server-side filtering, searching, sorting, and pagination.
9. Support for upcoming meals & publish-on-like logic.
10. Environment variables (.env) used for hiding sensitive credentials.

---

## 📁 Environment Variables (.env)

```env
PORT=5000
DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
ACCESS_TOKEN_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
