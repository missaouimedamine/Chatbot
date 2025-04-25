# AI Chatbot Platform 🌐💬

A multilingual chatbot platform with user authentication, chat history, and support for multiple AI models. Built with React (Vite) frontend and Django backend.


![image](https://github.com/user-attachments/assets/25cda621-e9b9-4a04-9e6d-3f418cf97e80)


![image](https://github.com/user-attachments/assets/833b9339-dc16-4f1d-9f03-64b8dd2cb9e9)

## Features ✨

- **User Authentication** 🔐
  - JWT-based login/logout
  - User registration
  - Protected routes

- **Multilingual Support** 🌍
  - English/Arabic interface
  - RTL layout for Arabic
  - i18n localization

- **Chat Interface** 💬
  - Multiple AI model selection
  - Conversation history
  - Responsive design

- **User Profile** 👤
  - Personal information
  - AI-generated interaction summary
  - Language preference

## Tech Stack 🛠️

**Frontend:**
- React 18 (Vite)
- React Router 6
- react-i18next (i18n)
- Framer Motion (animations)
- Tailwind CSS (styling)

**Backend:**
- Django 4.x
- Django REST Framework
- JWT Authentication
- SQLite (development)

## Project Structure 📂
project/
├── frontend/ # React/Vite application
│ ├── public/ # Static files
│ ├── src/
│ │ ├── components/ # Reusable components
│ │ ├── context/ # React contexts
│ │ ├── pages/ # Application pages
│ │ ├── services/ # API services
│ │ └── utils/ # Utilities and helpers
│ └── vite.config.js # Vite configuration
│
├── backend/ # Django project
│ ├── core/ # Main Django app
│ ├── api/ # REST API endpoints
│ ├── manage.py # Django CLI
│ └── requirements.txt # Python dependencies
│
└── README.md # Project documentation


## Installation ⚙️

### Frontend Setup

1. Navigate to frontend directory:
   ```bash
   cd frontend
Install dependencies:

bash
npm install
Start development server:

bash
npm run dev
Backend Setup
Navigate to backend directory:

bash
cd backend
Create virtual environment:

bash
python -m venv venv
source venv/bin/activate  # Linux/Mac)
venv\Scripts\activate     # Windows
Install dependencies:

bash
pip install -r requirements.txt
Run migrations:

bash
python manage.py migrate
Start development server:

bash
python manage.py runserver
Configuration ⚙️
Create .env files for both frontend and backend with appropriate environment variables:

Frontend (.env)

env
VITE_API_BASE_URL=http://localhost:8000/api
Backend (.env)

env
SECRET_KEY=your-django-secret-key
DEBUG=True
Available Scripts 🖥️
Frontend:

npm run dev - Start development server

npm run build - Build for production

npm run lint - Run ESLint

Backend:

python manage.py runserver - Start Django server

python manage.py makemigrations - Create migrations

python manage.py migrate - Apply migrations

Contributing 🤝
Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License 📄
This project is licensed under the MIT License - see the LICENSE file for details.
