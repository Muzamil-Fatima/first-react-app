# React + Tailwind CSS Setup using Vite

This project demonstrates how to create a React application using **Vite** and configure **Tailwind CSS** for styling.

## 📁 1. Create a React Project with Vite

Open your terminal and run the following steps:

```bash
# Navigate to your desired folder
cd path/to/your/projects

# Create a Vite-powered React project (replace 'my-react-app' with your desired project name)
npm create vite@latest my-react-app -- --template react

# Move into the project directory
cd my-react-app

# Install dependencies
npm install
````

---

## 🎨 2. Install Tailwind CSS and Configure

Install Tailwind CSS and its required dependencies:

```bash
npm install tailwindcss @tailwindcss/vite
```

### Configure the Vite Plugin

In your Vite config file (`vite.config.js` or `vite.config.ts`), add this:

```js
import tailwindcss from '@tailwindcss/vite' // <-- Add this line only


```

---

## 💅 3. Import Tailwind CSS

In your main CSS file (e.g., `src/index.css`), add the Tailwind directives:

```css
@import "tailwindcss";
```


---

## 🚀 4. Start the Development Server

Run the project locally:

```bash
npm run dev
```

The app will be available at:

```
http://localhost:5173/
```

> Hold down `Ctrl` and click the link in your terminal to open in your browser.

---

## ✅ Result

Now you have a fully working React + Vite + Tailwind CSS development environment.

Happy coding! 🎉

```

---

Let me know if you'd like a version with GitHub Pages or deployment instructions too!
```
