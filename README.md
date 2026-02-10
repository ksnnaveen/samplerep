# Work Order Management System

A full-stack application for managing work orders with React frontend and Python Flask backend.

## Project Structure

```
samplerep/
├── backend/           # Python Flask REST API
│   ├── app.py        # Flask application
│   ├── models.py     # Database models
│   ├── routes.py     # API routes
│   ├── config.py     # Configuration
│   ├── requirements.txt
│   ├── .env.example
│   └── README.md
├── frontend/         # React application
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── api.js
│   │   └── App.css
│   ├── package.json
│   ├── .env.example
│   └── README.md
├── .gitignore
└── README.md
```

## Quick Start

### Backend Setup

1. Navigate to backend directory:
```bash
cd backend
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the server:
```bash
python app.py
```

Backend will run on `http://localhost:5000`

### Frontend Setup

1. Navigate to frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

Frontend will run on `http://localhost:3000`

## API Endpoints

- `GET /api/workorders` - Get all work orders
- `GET /api/workorders/<id>` - Get a specific work order
- `POST /api/workorders` - Create a new work order
- `PUT /api/workorders/<id>` - Update a work order
- `DELETE /api/workorders/<id>` - Delete a work order

## Technology Stack

### Frontend
- React 18.2
- Axios (HTTP client)
- CSS3

### Backend
- Flask 2.3
- Flask-CORS (Cross-Origin Resource Sharing)
- Flask-SQLAlchemy (ORM)
- SQLite (Default database)

## Features

✅ Create work orders  
✅ View all work orders  
✅ Edit existing work orders  
✅ Delete work orders  
✅ Status and priority tracking  
✅ Assignment tracking  
✅ Due date management  
✅ Responsive UI  
✅ RESTful API

## Future Enhancements

- User authentication and authorization
- Work order comments/history
- File attachments
- Email notifications
- Advanced filtering and search
- Dashboard with analytics
- Mobile app

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.