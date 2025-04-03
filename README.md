<div align="center">
  
  <h3 align="center">Movie Scanner</h3>

   <div align="center">
     Built this project with the help of JSM detailed tutorial on <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> YouTube.
    </div>

</div>

## <a name="introduction">🤖 Introduction</a>

Built with React.js for the user interface, Appwrite for the Trending Movies Algorithm, and styled with TailwindCSS, The platform offers a sleek and modern experience for browsing and discovering movies.

## <a name="tech-stack">⚙️ Tech Stack</a>

- React.js
- Appwrite
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Browse All Movies**: Explore a wide range of movies available on the platform.
👉 **Search Movies**: Easily search for specific movies using a search function.
👉 **Trending Movies Algorithm**: Displays trending movies based on a dynamic algorithm.
👉 **Modern UI/UX**: A sleek and user-friendly interface.
👉 **Responsiveness**: Fully responsive design.

and many more, including code architecture and reusability


Follow these steps to set up the project locally on your machine.


Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)


Install the project dependencies using npm:

```bash
npm install
```

Create a new file named `.env.local` in the root of your project and add the following content:

```env
VITE_TMDB_API_KEY=

VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
```

Replace the placeholder values with your actual **[TheMovieDatabase API](https://developer.themoviedb.org/reference/intro/getting-started)** and **[Appwrite](https://apwr.dev/JSM050)** credentials. You can obtain these credentials by signing up on the [TheMovieDatabase](https://developer.themoviedb.org/reference/intro/getting-started) and creating a new project on the [Appwrite](https://apwr.dev)


```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

