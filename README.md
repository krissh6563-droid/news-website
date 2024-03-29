# News Website Using Django & News API
# Django News Aggregator Project


The Django News Aggregator Project is a web application that allows users to conveniently access and stay updated with the latest news articles from various sources. This project integrates the power of Django, a high-level Python web framework, with the News API, enabling real-time retrieval and display of news content.

## Features

- **User Authentication**: Users can create accounts, log in, and securely manage their profiles.

- **News Categories**: News articles are categorized into different topics, making it easy for users to explore news relevant to their interests.

- **Real-time Updates**: The application leverages the News API to fetch the latest news articles in real time.

- **Search Functionality**: Users can search for specific news articles using keywords and phrases.

- **Responsive Design**: The user interface is designed to be responsive and accessible on various devices, including desktops, tablets, and smartphones.

- **Saved Articles**: Logged-in users can save articles for later reading, allowing them to curate their own reading list.

- **Social Sharing**: Users can share interesting articles on social media platforms directly from the application.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/django-news-aggregator.git
   cd django-news-aggregator
   ```

2. Set up a virtual environment:
   ```
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Obtain a News API key:
   - Visit [News API](https://newsapi.org/) and sign up for an API key.
   - Copy the API key to your clipboard.

5. Configure the project settings:
   - Rename `config/settings_example.py` to `config/settings.py`.
   - Replace `'YOUR_NEWS_API_KEY'` with the actual API key you obtained.

6. Run migrations:
   ```
   python manage.py migrate
   ```

7. Start the development server:
   ```
   python manage.py runserver
   ```

8. Open your web browser and navigate to `http://localhost:8000` to access the application.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:
   ```
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them with descriptive commit messages.

4. Push your changes to your forked repository.

5. Create a pull request detailing your changes.

## Credits

This project is developed and maintained by [Shri Krishan](https://github.com/your-username).

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README file according to your project's specifics. Good luck with your Django News Aggregator project! If you have any questions or need assistance, please don't hesitate to contact us.
