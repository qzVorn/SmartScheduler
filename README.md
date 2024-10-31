# SmartScheduler

Smart Scheduler is, As the name specifies, a smart and minimilstic Task Scheduler helping elevate productivity and bring a new piece of product to the internet! This is solely a side-project and probably will not be pursued for a long period of time and will be cut short before its completed.

Project Structure:
```
smart-task-scheduler/
├── frontend/                 # React frontend application
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── contexts/        # React contexts
│   │   ├── hooks/          # Custom hooks
│   │   ├── services/       # API services
│   │   ├── types/          # TypeScript types
│   │   └── utils/          # Utility functions
│   └── package.json
│
├── backend/                  # Django backend application
│   ├── api/                 # API endpoints
│   ├── core/                # Core functionality
│   ├── tasks/              # Task management
│   ├── users/              # User management
│   ├── ml_service/         # Machine learning service
│   └── requirements.txt
│
└── README.md
```

# Setup Instructions:

1. Backend Setup:
```  
-bash - 
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
2. Frontend Setup:
```
bash
cd frontend
npm install
npm run dev
```

# Enviornment Variables:

1. Create `.env` file in frontend directory:
```
VITE_API_URL=http://localhost:8000/api
```
2. Create `.env` file in backend directory:
```
DEBUG=True
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=localhost,127.0.0.1
CORS_ALLOWED_ORIGINS=http://localhost:5173
```


Disclaimer: I did not make this, AI Did, All I did was Prompt Engineering, Quality Check, and actually putting it together and all the hard work other than the programming.
