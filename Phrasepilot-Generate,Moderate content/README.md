AI Content Manager
AI Content Manager is a Streamlit application designed to help users generate and moderate content using AI. It provides a user-friendly interface to generate content based on user prompts and moderate content based on various criteria. The app also includes features to track and analyze content generation and moderation activities.

Features
Content Generation: Generate content based on user prompts and selected parameters.
Content Moderation: Moderate content based on predefined categories and strictness levels.
History Tracking: View past generated and moderated content.
Analytics: Get insights into content generation and moderation activities.
Customizable Settings: Adjust content type, tone, length, and moderation criteria through a sidebar.
Installation
To run the AI Content Manager, you'll need to set up a Python environment and install the required packages. Follow these steps:

Clone the repository:

git clone https://github.com/cashilaa/bot-cont-mod.git
cd ai-content-manager

Set up a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:


pip install -r requirements.txt
Run the application:

streamlit run main.py
Usage
Open the app: Once the Streamlit server is running, open your browser and go to http://localhost:8501.

Generate Content:

Select content type, tone, maximum length, and moderation strictness from the sidebar.
Enter a prompt and click "Generate Content" to see the AI-generated content.
Moderate Content:

Enter the content you want to moderate and click "Moderate Content" to see the moderation results.
View History:

Check the "History" tab to review previously generated and moderated content.
Analyze Data:

Use the "Analytics" tab to view statistics about content generation and moderation activities.
Customization
You can customize the appearance and behavior of the app by modifying the following files:

styles.css: Update this file to change the CSS styles used in the app.
content_generator.py: Modify the content generation logic.
content_moderator.py: Adjust the content moderation rules and algorithms.
utils.py: Update utility functions used across the app.
Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/YourFeature).
Create a pull request.