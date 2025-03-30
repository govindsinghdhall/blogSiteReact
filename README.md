# blogSiteReact
# Blog Website

## Overview
This is a modern blog website built using **React.js** and **React Router**. It features dynamic routing, lazy loading, and API-based data fetching to provide a seamless reading experience.

## Features
- **Home Page**: Introduction and latest blog posts.
- **Blog Page**: Displays a list of all blog posts.
- **Post Page**: Shows details of a specific blog post.
- **Lazy Loading**: Uses `React.lazy()` and `Suspense` for optimized performance.
- **Dynamic Routing**: Implemented using `react-router-dom`.
- **Data Fetching**: Uses a loader function to fetch blog posts from an API.

## Tech Stack
- **Frontend**: React.js, React Router
- **State Management**: React Hooks
- **Styling**: CSS / Tailwind CSS (Optional)
- **Backend (API)**: Fetching from a mock API or Firebase (Optional)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/blog-website.git
   cd blog-website
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```

## Project Structure
```
/blog-website
│── public/          # Static assets
│── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Page components
│   │   ├── Home.js
│   │   ├── Blog.js
│   │   ├── Post.js
│   ├── App.js       # Main application component
│   ├── index.js     # Entry point
│── package.json
│── README.md        # Project documentation
```

## Deployment
To deploy your blog website:

1. Build the project:
   ```sh
   npm run build
   ```

2. Deploy to Firebase:
   ```sh
   firebase deploy
   ```

## Troubleshooting
- If you encounter a `posts.map is not a function` error, ensure that the API returns an array of posts.
- Upgrade Node.js if you face compatibility issues with Firebase:
  ```sh
  nvm install 20
  ```

## License
This project is open-source and available under the MIT License.

## Contact
For any issues or contributions, feel free to reach out at **govindsinghdhall@gmail.com**.

