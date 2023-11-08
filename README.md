# Django Blog

A comprehensive blogging platform developed with Django, allowing users to create, read, update, and delete blog posts. This application comes with user authentication, comment functionality, and a polished front-end display.

## Live Application

Visit the live application at [Django Blog](https://kc-django-blog.herokuapp.com/) to explore the features of this blogging site.

## Technology Stack

- **Framework**: Django
- **Database**: SQLite3
- **Front-End**: HTML, CSS, JavaScript
- **Deployment**: Heroku

## Installation and Setup

Ensure you have Python installed on your system. Then, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/kc-7/django-blog.git
   ```
2. Navigate to the project directory:
   ```sh
   cd django-blog-main
   ```
3. Install the requirements:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply the migrations:
   ```sh
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```

Access the application at `http://127.0.0.1:8000` in your web browser.

## Features

- Full CRUD functionality for blog posts.
- User registration and authentication system.
- Commenting feature on blog posts.
- Like and unlike functionality for posts.
- Responsive design for various device sizes.

## Usage

This platform is designed for users who wish to create and share content as well as engage with a community through comments and likes.

### Creating a Post

Users can create a blog post by navigating to the 'New Post' section after logging in.

### Interacting with Posts

Interact with posts by reading full articles, adding comments, and liking posts.

## Future Improvements

- Enhance styling and layout.
- Add favicon and custom branding.
- Improve user messaging for form interactions.
- Integrate social media single sign-on options.
- Implement comment count display.
- Utilize JavaScript Fetch API with Django for dynamic content updates.

## Acknowledgments

This project was completed as part of the Code Institute's Full Stack Developer Course. It serves as an educational tool to demonstrate comprehensive Django development skills.

