# Recipe Finder : React Application

A modern and interactive web application built with React and Vite, designed to help users discover and explore a variety of delicious recipes.

## Screenshots

1. ![Screenshot](/public/assets/screenshot-2.png)
---
2. ![Screenshot](/public/assets/screenshot-1.png)
---
3. ![Screenshot](/public/assets/screenshot-3.png)
---
4. ![Screenshot](/public/assets/screenshot-4.png)
---
5. ![Screenshot](/public/assets/screenshot-5.png)
---
6. ![Screenshot](/public/assets/screenshot-6.png)

## Features

*   **Extensive Recipe Collection**: Browse through a diverse range of recipes, each with detailed information.
*   **Detailed Recipe Views**: Access comprehensive details for each recipe, including ingredients, step-by-step instructions, cooking time, difficulty level, and more.
*   **Intuitive Navigation**: Seamlessly navigate between the home page, about section, and individual recipe details using React Router.
*   **Dynamic Data Loading**: Recipes are loaded from a local JSON file, making it easy to manage and extend the recipe database.
*   **Responsive Design**: Enjoy a consistent and user-friendly experience across various devices (implied by modern web development practices).
*   **Loading Animation**: A subtle loading animation enhances the user experience during initial application load.

## Technologies Used

*   **Frontend**:
    *   [React.js](https://react.dev/) - A JavaScript library for building user interfaces.
    *   [Vite](https://vitejs.dev/) - A fast build tool that provides a lightning-fast development experience.
    *   [React Router DOM](https://reactrouter.com/en/main) - Declarative routing for React.
    *   [React Icons](https://react-icons.github.io/react-icons/) - Popular icons for React projects.
    *   CSS for styling.

## Project Structure

```
.
├── public/                 # Static assets like images
├── src/
│   ├── components/         # React components (Home, About, Navbar, Footer, etc.)
│   │   └── subcomponents/  # Smaller, reusable components
│   ├── App.css             # Global CSS styles
│   ├── App.jsx             # Main application component and routing setup
│   ├── main.jsx            # React entry point
│   └── recipes.json        # JSON file containing all recipe data
├── .gitignore              # Specifies intentionally untracked files to ignore
├── eslint.config.js        # ESLint configuration
├── index.html              # Main HTML file
├── package.json            # Project metadata and dependencies
├── package-lock.json       # Records the exact dependency tree
├── README.md               # This file
├── vite.config.js          # Vite build configuration
└── node_modules/           # Installed Node.js modules
```


## Installation and Setup

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js (LTS version recommended)
*   npm (comes with Node.js)

### Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/saksham2882/recipe-finder.git
    cd recipe-finder
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```
    note: if npm install give error then use `npm install --legacy-peer-deps`

3.  **Run the development server:**
    ```bash
    npm run dev
    ```
    The application will be accessible at `http://localhost:5173` (or another port if 5173 is in use).

4.  **Build for production (optional):**
    ```bash
    npm run build
    ```
    This will create a `dist` folder with the production-ready build.

## Usage

*   Open your web browser and navigate to the development server URL (e.g., `http://localhost:5173`).
*   Browse through the available recipes on the home page.
*   Click on any recipe card to view its detailed information, including ingredients, cooking steps, and other attributes.
*   Use the navigation bar to switch between the Home and About pages.