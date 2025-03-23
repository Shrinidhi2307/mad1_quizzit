# QUIZZIT - Online Quiz Management System  
**A Flask-based platform for creating, managing, and tracking quizzes**  
*(Modern Application Development-I Project for IIT Madras BS in Data Science)*  

### 👩💻 User Features  
- **Secure Authentication**: Student/Admin login with role-based access  
- **Quiz Interface**: Attempt quizzes with real-time timers  
- **Performance Tracking**: View attempt history and detailed score reports  
- **Search System**: Find quizzes by subject/chapter  
- **Feedback System**: Rate quizzes after completion  

### 👨💼 Admin Features  
- **Content Management**:  
  - Create/Edit/Delete Subjects & Chapters  
  - Build quizzes with MCQ questions (single correct answer)  
- **User Management**:  
  - Manage student accounts  
  - Track student performance metrics  
- **Analytics Dashboard**:  
  - Visualize quiz participation statistics  
  - Generate score distribution charts  

## 🛠 Technologies Used  
| Component          | Technology Stack |  
|---------------------|------------------|  
| Backend Framework   | Flask            |  
| Database ORM        | SQLAlchemy       |  
| Frontend            | Jinja2 + Bootstrap |  
| Data Visualization  | Plotly           |  
| Task Scheduling     | APScheduler      |  

## 🚨 Getting Started  

### Prerequisites  
- Python 3.8+  
- pip package manager  

### Installation  
```bash  
# Clone repository  
git clone https://github.com/yourusername/quiz_master.git  
cd quiz_master  

# Create virtual environment  
python -m venv venv  

# Activate environment (Windows)  
venv\Scripts\activate  

# Install dependencies  
pip install -r requirements.txt  
```

### Database Setup  
```bash  
flask shell  
>>> from app import create_app, db  
>>> app = create_app()  
>>> app.app_context().push()  
>>> db.create_all()  
>>> exit()  
```

### Running the Application  
```bash  
flask run  
```
Access at: http://localhost:5000  

## 🔑 Default Credentials  
| Role    | Username | Password |  
|---------|----------|----------|  
| Admin   | admin    | admin123 |  
| Student | user     | user123  |  

## 📂 Project Structure  
```  
quiz_master/  
├── app/  
│   ├── templates/      # HTML templates  
│   ├── static/         # CSS/JS assets  
│   ├── models.py       # Database models  
│   └── routes.py       # Application routes  
├── requirements.txt    # Dependencies  
└── config.py           # Configuration settings  
```

## 📈 Analytics Preview  
![Quiz Analytics Dashboard](docs/anale analytics dashboard showing student performance metrics*

## 🤝 Contributing  
1. Fork the repository  
2. Create feature branch: `git checkout -b new-feature`  
3. Commit changes: `git commit -am 'Add new feature'`  
4. Push branch: `git push origin new-feature`  
5. Submit pull request  



