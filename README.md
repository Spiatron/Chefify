
# 🍳 Chefify

Chefify is a modern recipe management and generation platform. This project utilizes cutting-edge web technologies to provide users with an engaging experience for creating, exploring, and managing recipes. With features like AI-powered recipe generation, user authentication, and a stunning UI, Chefify redefines how you interact with culinary content.

---

## 🚀 Features

- **AI Recipe Generator**: Create unique recipes using AI.
- **Interactive Gallery**: Explore recipes with an engaging interface.
- **User Profiles**: Personalized user experience with authentication.
- **Responsive Design**: Fully responsive UI built with Tailwind CSS.
- **API Integration**: Robust APIs for generating, saving, and fetching recipes.
- **Real-Time Suggestions**: Quick and dynamic recipe suggestions.

---

## 🛠️ Requirements

Ensure you have the following installed before proceeding:

1. [Node.js](https://nodejs.org/en)
2. [XAMPP](https://www.apachefriends.org)
3. [Visual Studio Code (VS Code)](https://code.visualstudio.com)

---

## 📦 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/YourGitHubProfile/Chefify.git
cd Chefify
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Database Setup

1. Start the **MySQL** service in the **XAMPP Control Panel**.
2. Configure the `DATABASE_URL` in the `.env` file with your MySQL database connection string.
3. Push the database schema using Prisma:

```bash
npx prisma db push
```

### Step 4: Run the Development Server

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

---

## 📑 Project Structure

- **API Routes**: Located in `src/app/api/` for handling authentication, recipe generation, and database interactions.
- **Components**: Modular components in `src/app/components/` for building the user interface.
- **Styles**: Custom styles in `src/app/styles/`.
- **Prisma Schema**: Database schema in `prisma/schema.prisma`.

---

## ⚠️ Troubleshooting

- **Environment Variables**: Double-check your `.env` configuration for accuracy.

---

## 🤝 Contributing

We welcome contributions to improve Chefify! Follow these steps:

1. **Fork the Repository**: Create your own copy.
2. **Create a New Branch**: Use a descriptive name:
   ```bash
   git checkout -b feature-branch-name
   ```
3. **Commit Your Changes**: Write clear commit messages:
   ```bash
   git commit -m "Add feature: description"
   ```
4. **Push to Your Branch**: Upload your changes:
   ```bash
   git push origin feature-branch-name
   ```
5. **Submit a Pull Request**: Explain your changes and submit a PR.

---

## 📧 Contact

For support, feedback, or inquiries, reach out to us:

- **Email**: [ahsanhafeez506@gmail.com](mailto:ahsanhafeez506@gmail.com)
- **GitHub**: [Ahsan Hafeez](https://github.com/Spiatron)
- **Linkedln**: [Ahsan Hafeez](https://www.linkedin.com/in/ahsan-hafeez-116943278/)
