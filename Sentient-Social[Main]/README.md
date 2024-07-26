# Sentient Social Media

Sentient Social Media is an AI-powered social networking platform that leverages advanced language models to create engaging content and maintain a safe community environment.

## Features

- AI-driven content generation and moderation with PhrasePilot
- User authentication and profiles
- Post creation, liking, and commenting
- Follow/unfollow functionality
- Media upload support (images and videos)
- Community guideline enforcement

## Technology Stack

- Backend: Python, Flask
- Database: SQLite with SQLAlchemy ORM
- AI: Google's Generative AI (Gemini)
- Frontend: HTML, CSS (Tailwind CSS), JavaScript

## Installation

1. Clone the repository:
git clone https://github.com/cashilaa/sentient-social.git
cd sentient-social-media

2. Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate

3. Install the required dependencies:
pip install -r requirements.txt

4. Set up environment variables:
Create a `.env` file in the root directory and add the following:
SECRET_KEY=your_secret_key
GEMINI_API_KEY=your_gemini_api_key

5. Initialize the database:
flask db upgrade

6. Run the application:
python app.py

7. Open your browser and navigate to `http://localhost:5000`

## Project Structure

- `app.py`: Main Flask application
- `main.py`: PhrasePilot bot implementation
- `moderator.py`: Content moderation logic
- `generator.py`: Content generation logic
- `user_interests.py`: User interests management
- `guidelines.py`: Community guidelines
- `templates/`: HTML templates
- `static/`: Static files (CSS, JS, uploads)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.



## Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Google Generative AI](https://ai.google.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Contact

For any queries or feedback, please open an issue on this repository.