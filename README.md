# 📹 Video Conferencing App

## 🚀 Table of Contents

1. [📦 Technologies Used](#technologies-used)
2. [🔧 Installation](#installation)
3. [💻 Usage](#usage)
4. [📄 Key Pages](#key-pages)
5. [✨ Features](#features)

---

## 📦 Technologies Used

- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework for rapid UI development.
- **[React.js](https://react.dev/)** - JavaScript library for building user interfaces.
- **[Next.js](https://nextjs.org/)** - React framework for server-rendered applications.
- **[Clerk](https://clerk.dev/)** - Frontend user management platform for authentication and user management.
- **[Stream](https://getstream.io/)** - Scalable and secure chat and video application services.

---

## 🔧 Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Hatalabdallah/Zoom-clone.git
   cd Zoom-clone
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   - Create a `.env.local` file in the root directory.
   - Add your Clerk and Stream API keys:

     ```env
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
     CLERK_SECRET_KEY=""

     NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
     NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

     NEXT_PUBLIC_STREAM_API_KEY=""
     STREAM_SECRET_KEY=""
     ```

---

## 💻 Usage

To start the development server, run:

```bash
npm run dev
```

Visit [`http://localhost:3000`](http://localhost:3000) in your browser to view and interact with the app.

---

## 📄 Key Pages

- **Sign In:** `/sign-in` - Authentication page for user login.
- **Create Meeting:** `/create-meeting` - Interface to create new meetings.
- **Join Meeting:** `/join-meeting` - Page to join existing meetings.
- **Meeting Room:** `/meeting/:meetingId` - The main meeting interface featuring video calls, chat, and more.

---

## ✨ Features

- **User Authentication:** Secure login and registration with Clerk.
- **Video and Audio Calls:** High-quality video conferencing powered by Stream.
- **Screen Sharing:** Effortlessly share your screen with meeting participants.
- **Chat:** Engage in real-time messaging during meetings.
- **Meeting Rooms:** Seamlessly create and join meeting rooms.
- **Responsive Design:** Accessible and fully responsive UI built with Tailwind CSS.

---

### 🎨 Enjoy using the Video Conferencing App!

Feel free to reach out if you have any questions or need assistance. Happy conferencing! 🎉

---

This format provides clarity and organization for users navigating your documentation. Let me know if you need any more adjustments!