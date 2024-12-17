# PixGenie

**Transform your Ideas with PixGenie: Powered by AI, Inspired by Magic!**

PixGenie is a modern AI-powered SaaS application designed to seamlessly transform your creative ideas into reality. Whether you're editing or modifying images, PixGenie combines the power of **AI** with a touch of magic to deliver exceptional user experiences.

## ✨ Built With

- **Next.js 14** - Modern React framework for fast, server-rendered applications.
- **TypeScript** - For type-safe development and maintainable code.
- **Cloudinary** - Streamlined media storage and management.
- **Clerk** - Secure and easy-to-implement user authentication.
- **Stripe** - Simple and efficient payment integration for monetization.

---

Let **PixGenie** be your creative companion and turn your visions into captivating visuals effortlessly! 🚀



## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/PixGenie.git
cd PixGenie
```

**Installation**

Install the project dependencies using npm:

```bash
npm run dev
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
