# **Startup Universe: Where Ideas Ignite and Innovators Unite!**

Startup_Universe is a Next.js platform where entrepreneurs can submit their startup ideas for virtual pitch competitions, browse other pitches, and gain exposure through a clean, minimalistic design for a smooth user experience. This repository contains the source code and setup instructions for building the platform.

## 🔥 Features

- **Live Content API**: Displays the latest startup ideas dynamically on the homepage using Sanity's Content API.
- **GitHub Authentication**: Easy login via GitHub.
- **Pitch Submission**: Users can submit their ideas with title, description, category, and multimedia links.
- **Browse Pitches**: Filter and view startup ideas by category.
- **Pitch Details Page**: Detailed view of any pitch, including multimedia.
- **User Profile**: List of pitches submitted by a user.
- **Editor Picks**: Admins can highlight top ideas via Sanity Studio.
- **Views Counter**: Tracks pitch popularity through views.
- **Search**: Efficiently search for pitches.
- **Minimalistic Design**: Fresh UI with essential pages for a seamless experience.

---

## ⚙️ Tech Stack

- **Frontend**: React 19, Next.js 15, TailwindCSS, ShadCN, TypeScript
- **Backend**: Sanity (CMS)
- **Authentication**: GitHub OAuth

---

## 🤸 Quick Start

Follow these steps to set up the project on your local machine.

### Prerequisites

Ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (v16 or above)
- npm (Node Package Manager)

---

### 🚀 Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/manohar4229/Startup_Universe.git
   cd Startup_Universe
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**

   Create a new file named `.env.local` in the root of the project and add the following:

   ```plaintext
   NEXT_PUBLIC_SANITY_PROJECT_ID=<your_project_id>
   NEXT_PUBLIC_SANITY_DATASET=<your_dataset>
   NEXT_PUBLIC_SANITY_API_VERSION='vX'
   SANITY_TOKEN=<your_sanity_token>

   AUTH_SECRET=<auth_secret>
   AUTH_GITHUB_ID=<github_client_id>
   AUTH_GITHUB_SECRET=<github_client_secret>
   ```

   Replace the placeholder values with your credentials. You can get them by creating a new project on [Sanity](https://www.sanity.io/).

4. **Run the Project**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

---

Happy Coding! 🚀
