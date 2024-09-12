# Parser_Python
Create a `README.md` with setup instructions:

markdown
->ResumeProcessor

->Setup Instructions

1. Clone the repository.
2. Install dependencies:
   bash
   pip install -r requirements.txt
   
3. Configure PostgreSQL settings in `ResumeProcessor/settings.py`.
4. Run migrations:
   bash
   python manage.py migrate
   
5. Start the server:
   bash
   python manage.py runserver
   
6. Test the API at `/resume/api/extract_resume/` by uploading a resume.

## 10. Testing the API:

Test the `/resume/api/extract_resume/` endpoint using Postman:

- Method: `POST`
- URL: `http://127.0.0.1:8000/resume/api/extract_resume/`
- Body: Choose form-data and upload the resume as `resume` (key).
