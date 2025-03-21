# Information Integrity Monitoring
A web application built with Python Django and Machine Learning that detects fake news using a Multinomial Naive Bayes Classifier. The project provides users with a platform to validate the authenticity of news and view their analysis history.
A web-based platform developed to detect fake news using Machine Learning and Natural Language Processing (NLP) techniques. This system ensures high detection accuracy and reliable performance, offering a seamless user experience through an intuitive interface and robust backend.
# Features
## Fake News Detection:
  Utilizes a Multinomial Naive Bayes Classifier for analyzing and predicting the authenticity of news articles.
  Achieved a detection accuracy of 90% using Python and scikit-learn. -User Authentication:
  Supports secure sign-up and login functionalities.
  User-specific prediction history is stored and managed in the database.
## Responsive Front-End:
  Developed using HTML, CSS, and jQuery to provide a smooth and consistent user experience across devices.
## Database Integration:
  All user interactions and prediction history are efficiently stored in an SQLite database.
# Setup Instructions
## Clone the Repository
  git clone https://github.com/YourUsername/Information-Integrity-Monitoring-System.git
  cd Information-Integrity-Monitoring-System
## Create a Virtual Environment
  python -m venv env
## Install Dependencies
  pip install -r requirements.txt
## Apply Migrations
  python manage.py migrate
## Start the Development Server
  python manage.py runserver
