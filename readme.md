# JWT Authentication in Express

## Main Features
- Role-based access control
- Custom middleware implementation
- JSON Web Token (JWT) authentication
- Prisma ORM for database operations
- MySQL database integration
- Cookie-based token storage
- HTTP-only cookie security

## Getting Started

Clone the repository:

```bash
git clone https://github.com/jk08y/jwt-authentication-for-express.git
cd express-jwt-start
```

## Installation

Install dependencies:

```bash
npm install
```

## Environment Configuration

Create a `.env` file with the following contents:

```
# SERVER
PORT=8000

# JWT
ACCESS_TOKEN_SECRET=access_token_secret
ACCESS_TOKEN_EXPIRED=30
REFRESH_TOKEN_SECRET=refresh_token_secret
REFRESH_TOKEN_EXPIRED=30

# DATABASE
DATABASE_URL=
```

## Database Setup

Configure your MySQL database with Prisma:

```bash
npx prisma generate
npx prisma db push
```

## Usage Commands

| Command                | Description                               |
| ---------------------- | ----------------------------------------- |
| `npm run dev`          | Launch development server                 |
| `npm run prettier`     | Verify code formatting with Prettier      |
| `npm run prettier:fix` | Automatically fix formatting issues       |