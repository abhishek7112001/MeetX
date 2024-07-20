# MeetX

Welcome to **MeetX**, a cutting-edge, professional video conferencing application designed to meet the needs of enterprises. Built with the latest technologies, including **Next.js**, **Tailwind CSS**, **TypeScript** and **Stream**, MeetX offers a seamless and reliable video communication experience.

![Thumbnail](/meetx.png)

## Features

- **User-friendly Interface**
- **Clerk Authentication**
- **Meeting Room**
- **Previous Meeting Page**
- **Dynamic Content Rendering**

## <a name="tech-stack">Tech Stack</a>

- Next.js
- TypeScript
- Stream
- Shadcn
- Tailwind CSS

## <a name="quick-start">Integration and Installation Process</a>

Follow these steps to set up the project locally on your device.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

To get started with **Marketory**, follow these steps:

1. **Clone the Repository**:
   ```shell
   git clone https://github.com/prashant-sagar-shakya/MeetX.git
   ```
2. **Install Dependencies**:
   ```shell
   cd MeetX
   npm install
   ```
3. **Start the Development Server**:
   ```shell
   npm run dev
   ```
4. **Access the Website**: Open your browser and navigate to `http://localhost:3000` to access the website.

5. **Set Up Environment Variables**: Create a new file named `.env` in the root of your project and add the following content:

   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

   NEXT_PUBLIC_STREAM_API_KEY=
   STREAM_SECRET_KEY=
   NEXT_PUBLIC_BASE_URL=
   ```

## <a name="contribution">Contribution</a>

Contributions are welcome, Happy Coding !!!
