🌐 HomelyHub – Hotel Booking Website (Frontend)

This is the frontend of the HomelyHub Hotel Booking Platform, built using React + Vite.
The UI enables users to browse hotels, view room details, book accommodations, and manage their booking experience seamlessly.

🚀 Features
🏨 User Features

Browse available hotels and rooms

View detailed hotel information

Search and filter options

Login & Register

Book a room and view booking status

Responsive UI for mobile and desktop

🛠️ Tech Stack

React JS

Vite

JavaScript (ES6+)

Axios for API calls

React Router DOM

CSS 


📁 Project Structure
frontend/

├── public/

├── src/

│   ├── components/

│   ├── pages/

│   ├── hooks/

│   ├── context/

│   ├── utils/

│   └── App.jsx

├── .gitignore

├── index.html

├── package.json

├── vite.config.js

└── README.md

⚙️ Installation & Setup

Follow the steps below to run the frontend locally:

1. Clone the repository
git clone https://github.com/Anusha-P-N/hotel-booking-frontend.git

2. Navigate into the project
cd hotel-booking-frontend

3. Install dependencies
npm install

4. Start development server
npm run dev

🔗 API Connection

The project uses Vite proxy for local backend communication:

// vite.config.js

server: {

  proxy: {
  
    '/api': {
    
      target: 'http://localhost:8000',
      
      changeOrigin: true,
      
      secure: false,
      
    }
  }
}


Make sure your backend is running on port 8000.

📦 Build for Production

To build the frontend:

npm run build

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
