# 🎵 AI Songwriter

**Your creative partner for writing lyrics and composing audio tracks using the power of AI.**

![AI Songwriter App Screenshot](./client/public/app-screenshot.jpg)

---

## ✨ About The Project

AI Songwriter is a full-stack web application designed to break through creative blocks. It provides a seamless, step-by-step workflow to go from a simple idea to a complete song draft, including both lyrics and a fully-rendered audio track.

**Key Features:**
*   ✍️ **AI-Powered Lyrics Generation:** Describe a theme, genre, and mood, and get unique lyrics in seconds.
*   🎹 **AI-Powered Audio Composition:** Generate a high-quality `.mp3` or `.wav` audio track that matches the tone of your lyrics.
*   🎧 **In-Browser Audio Player:** Listen to your new composition right away.
*   ☁️ **Cloud Storage:** All generated audio files are securely stored on Google Cloud Storage.
*   🔒 **User Authentication:** Sign up to save your song projects and build your personal songbook.
*   😎 **Custom-Built UI:** A beautiful, bespoke interface with dark/light modes, built from scratch with React and Tailwind CSS.

## 🚀 Tech Stack

This project showcases a modern, robust full-stack architecture.

*   **Frontend:** [Next.js](https://nextjs.org/) (React) with [Tailwind CSS](https://tailwindcss.com/)
*   **Backend:** [Node.js](https://nodejs.org/) with [Express.js](https://expressjs.com/)
*   **Database:** [PostgreSQL](https://www.postgresql.org/)
*   **Cloud Storage:** [Google Cloud Storage (GCS)](https://cloud.google.com/storage)
*   **AI Services:**
    *   Text Generation: [OpenAI API](https://openai.com/api/)
    *   Audio Generation: [Replicate](https://replicate.com/) (e.g., MusicGen)
*   **Deployment:**
    *   Frontend on [Vercel](https://vercel.com/)
    *   Backend on [Render](https://render.com/)

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js (v18 or later)
*   npm or yarn
*   A running PostgreSQL instance
*   Google Cloud SDK configured for GCS access

### Installation

1.  **Clone the repo**
    ```sh
    git clone https://github.com/poitouBenjamin/AI-Songwriter.git
    cd AI-Songwriter
    ```

2.  **Set up Backend (`/server`)**
    *   Navigate to the server directory: `cd server`
    *   Install NPM packages: `npm install`
    *   Create a `.env` file based on `.env.example` and fill in your variables (Database URL, GCS credentials, API Keys, etc.).
    *   `cd ..` to go back to the root.

3.  **Set up Frontend (`/client`)**
    *   Navigate to the client directory: `cd client`
    *   Install NPM packages: `npm install`
    *   Create a `.env.local` file and add `NEXT_PUBLIC_API_URL=http://localhost:3001`.

4.  **Run the application**
    *   From the `/server` directory, run `npm run dev` to start the backend.
    *   From the `/client` directory, run `npm run dev` to start the frontend.
    *   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
