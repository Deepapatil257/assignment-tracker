Assignment Tracker - Prototype Submission

✅ Features Implemented:
- User signup/login with JWT token
- Role-based access (Teacher/Student)
- Assignment creation by teacher
- Submission by student
- View submissions by teacher
- Tested with Postman & HTML Forms

✅ How to Run:
1. Install Python packages: pip install -r requirements.txt
2. Run FastAPI server: python -m uvicorn main:app --reload
3. Open frontend HTML using: python -m http.server 8080
4. Test API with Postman or HTML forms

Note:  
- Access tokens must be freshly obtained via login.  
- Tokens expire after 30 minutes by design (can be adjusted in code).  
- If server restarts, login again to get a new token.  
- This is standard JWT-based authentication behavior.

✅ Note:
This is a functional prototype focused on backend API and basic frontend for testing.

