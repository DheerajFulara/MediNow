# MediNow – Doctor Appointment & Video Consultation Platform  

MediNow is a **Full-Stack Doctor Appointment Platform** where patients can easily search for doctors, book appointments, and take **online video consultations**. Doctors can manage their schedules, conduct consultations via secure video calls, and receive payments for their services.  

The platform integrates **Next.js, Neon (Postgres), Clerk, Tailwind, Shadcn UI, and Vonage** to provide a seamless healthcare booking and telemedicine experience.  

---

## 📖 About  

MediNow provides an end-to-end solution for digital healthcare:  

- Patients can **browse doctors by specialty**, **book appointments**, and **consult via video calls**.  
- Doctors can **set availability**, **conduct secure video consultations**, and **charge patients per session**.  
- The system handles **authentication, scheduling, payments, and notifications**.  

✨ Key highlights:  
- 👨‍⚕️ **Doctor & Patient Portals** – Separate dashboards for both roles.  
- 📅 **Smart Appointment Booking** – Real-time doctor availability and clash-free scheduling.  
- 📹 **Video Consultation** – Powered by **Vonage API** for secure calls.  
- 💳 **Payment Integration** – Patients are charged for each consultation.  
- 🔐 **Authentication** – Managed with **Clerk** (secure login & onboarding).  
- 🎨 **Modern UI** – Tailored with **Tailwind CSS** and **Shadcn UI**.  
- 🗄 **Database** – Cloud-hosted **Neon PostgreSQL**.  

---

## 🚀 Features  

- 🧑‍🤝‍🧑 **Patient Dashboard** – Manage profile, bookings, and video calls.  
- 👨‍⚕️ **Doctor Dashboard** – Manage schedules, consultations, and earnings.  
- 🔐 **Secure Authentication** – Clerk-based login/signup & onboarding.  
- 📲 **Notifications** – Appointment confirmations/reminders via Vonage.  
- 📹 **Telemedicine Support** – One-click join video consultation.  
- 💳 **Payments** – Session-based consultation charges.  
- 📊 **Admin Panel** – Manage users, doctors, and transactions.  
- 📱 **Fully Responsive** – Works seamlessly across desktop and mobile.  

---

## 🛠️ Tech Stack  

**Frontend & Backend**  
- ⚡ [Next.js](https://nextjs.org/) – Full-stack React framework  
- 🎨 [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework  
- 🖌 [Shadcn UI](https://ui.shadcn.com/) – UI components  

**Authentication**  
- 🔑 [Clerk](https://clerk.dev/) – User authentication & onboarding  

**Database**  
- 🗄 [Neon](https://neon.tech/) – Serverless PostgreSQL  

**Video & Notifications**  
- 📹 [Vonage API](https://www.vonage.com/) – Video calls, SMS, notifications  

**Other Tools**  
- 🚀 Vercel – Hosting & deployment  
- 🛢 Prisma – ORM for Neon PostgreSQL  

---

## 📥 Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/DheerajFulara/MediNow.git
2. Install dependencies:
   ```bash
   npm install
3. Create a .env.local file in the root and add the following variables:
   ```bash
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=clerk key
    CLERK_SECRET_KEY=clerk secret key
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
    
    NEXT_PUBLIC_VONAGE_APPLICATION_ID=write your vonage id
    VONAGE_PRIVATE_KEY=lib/private.key
    
    DATABASE_URL=write your neon db key
 4. Run the development server:
    ```bash
    npm run dev
---







