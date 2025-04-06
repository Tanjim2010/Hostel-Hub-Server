
---

## ✅ Server Side `README.md`:

```md
# Hostel Hub - Server Side

🖥️ **Live Server:** [https://hostel-hub-server-six.vercel.app](https://hostel-hub-server-six.vercel.app)

---

## 🛠️ Features:
1. User authentication with JWT and role-based access control.
2. MongoDB database with secure access using environment variables.
3. Admin routes for user management, meal management, and reviews.
4. Upcoming meals system with publish on like threshold.
5. Stripe payment integration for purchasing premium memberships.
6. Server-side pagination and sorting for dashboard tables.
7. Server-side filtering and searching for meals and users.
8. Secure .env configuration and hidden credentials in GitHub.
9. Custom middlewares for verifying JWT and admin roles.
10. RESTful API structure with meaningful responses and error handling.

---

## 🔧 Technologies Used:
- Node.js
- Express.js
- MongoDB
- dotenv
- CORS
- JSON Web Token (JWT)
- Stripe API

---

## 📁 Environment Variables (.env)
```env
PORT=5000
DB_USER=your_db_username
DB_PASS=your_db_password
ACCESS_TOKEN_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
