# Virtual Hiring Interview Platform
<p>Virtual Hiring & Interview Platform is a web-based solution designed to streamline the interview process for both recruiters and candidates. 
  <br/>It provides an intuitive interface for recruiters to schedule, manage, and conduct interviews, while offering a hassle-free, one-click video call experience for candidates.</p>

![image](https://github.com/user-attachments/assets/00277ab0-d2d2-404e-8936-7e2463b6eb8e)


🚀 Tech Stack & Features
- Framework & Language: Built with Next.js and TypeScript for a modern, scalable frontend architecture.
- Video Communication: Integrated with Stream to enable seamless, high-quality video calls.
- Real-Time Collaboration: Supports screen sharing and live coding for interactive interview experiences.
- Session Recording: Enables screen recording for future review and feedback.
- Authentication & Authorization: Secure login and user management powered by Clerk.
- Backend & Database: Utilizes Convex for real-time backend operations and data handling.
- Modern Next.js Features: Implements Server Components, Layouts, and Server Actions for optimized performance.
- Routing: Includes both dynamic and static routing for flexible navigation.
- Styling: Styled using Tailwind CSS and enhanced with Shadcn UI components.
- Client-Server Architecture: Thoughtfully structured with a clean separation of Client and Server Components

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

### Run the app

```shell
npm run dev
```

```shell
mpx convex dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
