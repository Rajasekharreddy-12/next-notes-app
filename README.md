# 📝 Next.js MongoDB CRUD Notes App

![Next.js](https://img.shields.io/badge/Next.js-13.5-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-38B2AC?style=for-the-badge&logo=tailwind-css)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)

A fully functional **Full Stack Notes Application** built to demonstrate CRUD (Create, Read, Update, Delete) operations. This project utilizes the **Next.js 13 App Router** for the frontend and API routes, styled with **Tailwind CSS**, and persists data using **MongoDB** via **Mongoose**.

---

## 🌟 Features

* **⚡ Full Stack Architecture:** Server-side rendering and API handling within Next.js.
* **bm CRUD Operations:**
    * **Create:** Add new notes with a title and description.
    * **Read:** View a list of all notes and details of specific notes.
    * **Update:** Edit existing note content.
    * **Delete:** Remove notes from the database.
* **🎨 Responsive UI:** Built with Tailwind CSS for a mobile-first, clean interface.
* **🗄️ Database:** Integrated with MongoDB Atlas using Mongoose for schema-based modeling.
* **🔔 Notifications:** (Optional - if applicable) visual feedback on user actions.

---

## 🛠️ Tech Stack

| Component | Technology | Version |
| :--- | :--- | :--- |
| **Framework** | [Next.js](https://nextjs.org/) | 13.5.4 |
| **Frontend Library** | [React](https://reactjs.org/) | 18 |
| **Database** | [MongoDB Atlas](https://www.mongodb.com/) | Cloud |
| **ORM/ODM** | [Mongoose](https://mongoosejs.com/) | 7.6.2 |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) | 3.3 |
| **Icons** | [React Icons](https://react-icons.github.io/react-icons/) | 4.11.0 |

---

## 🚀 Getting Started

Follow the instructions below to set up the project on your local machine.

### Prerequisites

* **Node.js**: Ensure you have Node.js installed (v16+ recommended).
* **MongoDB Atlas Account**: You need a connection string to a MongoDB database.

### 📥 Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/nextjs-mongodb-crud-notes-web-app.git](https://github.com/your-username/nextjs-mongodb-crud-notes-web-app.git)
    cd nextjs-mongodb-crud-notes-web-app
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

### 🔐 Environment Configuration

This project uses environment variables to securely connect to the database. You must create a local environment file.

1.  Create a file named `.env.local` in the root directory.
2.  Add your MongoDB connection string to it:

    ```env
    MONGODB_URI=mongodb+srv://<db_username>:<db_password>@cluster0.example.mongodb.net/notesapp
    ```

    > ⚠️ **Important:** Replace `<db_username>` and `<db_password>` with your actual MongoDB Atlas credentials. Do not wrap them in quotes.

### 🏃‍♂️ Running the App

Start the development server:

```bash
npm run dev
