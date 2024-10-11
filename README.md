
# Career Steps

**Career Steps** is an innovative Django web application that assists students and employees in making informed career decisions. It leverages voice commands, supports over 110 languages, and uses machine learning to predict future career paths based on an individual's interests and study habits. With access to mentors, detailed career information, and a powerful chatbot, this app is a one-stop solution for career guidance.

## Features

- **Voice-Operated Interface**: Fully functional web app controlled by voice commands, making it user-friendly and accessible.
- **110+ Language Support**: Global reach with support for over 110 languages.
- **Machine Learning Predictions**: Predicts career paths based on a student’s interests and learning patterns using ML models.
- **Comprehensive Career Guidance**: Provides a full career path including:
  - Relevant exams
  - Top institutions
  - Detailed career-related information
- **Mentorship Program**: Connects users with professional mentors for personalized guidance.
- **AI-Powered Chatbot**: Automated responses generated through an ML model to assist with career-related queries.

## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: Used for career prediction and chatbot responses
- **Voice Command Integration**: Supports voice-based interaction across the entire app
- **Database**: PostgreSQL or MySQL for managing user data, career paths, and mentorship programs

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Narendra1920/Career-Steps
   ```

2. Navigate to the project directory:

   ```bash
   cd Career-Steps
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations to set up the database:

   ```bash
   python manage.py migrate
   ```

5. Run the Django development server:

   ```bash
   python manage.py runserver
   ```

## Usage

1. **Sign Up**: Users (students or employees) can sign up and create their profiles.
2. **Voice Commands**: The entire app can be navigated and operated using voice commands.
3. **ML-Based Career Predictions**: Enter your interests and study habits, and the app will suggest personalized career paths.
4. **Mentorship**: Connect with professional mentors for career advice.
5. **Chatbot**: Ask career-related questions, and the AI-powered chatbot will respond with relevant information.

## ML Model for Prediction

The app uses a machine learning model trained on various datasets to predict the most suitable career paths based on:
- Interests
- Study patterns
- Academic performance

The model takes into account user data and suggests potential career options, along with guidance on exams, institutions, and career milestones.

## Voice Command System

The app is entirely operated through voice commands, providing a hands-free experience. Users can:
- Search for career paths
- Navigate through different sections
- Ask the chatbot questions
- Access mentorship programs

## Mentorship Program

Career Steps connects users with mentors from various fields who provide:
- Personalized career advice
- Guidance on exam preparation
- Institution recommendations

## Chatbot

The app comes with a built-in chatbot that provides real-time, automated responses. The chatbot is trained using machine learning models to answer career-related queries, offering students and employees the information they need to make informed decisions.

## Future Enhancements

- Expanding the mentorship network
- Integration with more global exams and institutions
- Improved prediction accuracy using deep learning models
- Expanding voice command features to include more complex interactions

## License

This project is licensed under the MIT License.

## Acknowledgements

We would like to thank all the mentors and data scientists involved in creating the prediction models and enhancing the chatbot system.


