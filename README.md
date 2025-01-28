# Django Blog Website

This project is a full-fledged blog website built using Django, a high-level Python web framework. designed for creating, managing, and sharing blog posts. 
## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication:** Secure user registration, login, reset password, and profile management.
- **Blog Management:** On the home page, you can view the latest blog posts and can navigate through multiple pages of blog posts using pagination.
- **Interaction:** Authenticated users can add, update, and remove blog posts.
- **Responsive Design:** Mobile-friendly UI ensuring a consistent experience across devices.
- **Admin Panel:** Manage posts and users efficiently through Django's admin interface.

## Technologies Used

- **Django:** Python-based web framework for backend development.
- **HTML/CSS/JavaScript:** Frontend development for a responsive and interactive UI.
- **Bootstrap:** Frontend framework for responsive design and UI components.
- **Django Crispy Forms (Form):** It provides  |crispy filter and {% crispy %} tag that will let you control the rendering behavior of your Django forms.

## Setup Instructions

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone git@github.com:ydvprbn/django-blogg-project.git
   cd django-blogg-project
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   ```
3. **Activate the virtual environment:**

   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (admin):**

   ```bash
   python manage.py createsuperuser
   ```

7. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

8. **Open your web browser and navigate to:** 
   ```bash
   http://127.0.0.1:8000/
   ```

## Contributing

I welcome contributions from the developer community to help improve and grow the Django Blog project. Whether you're interested in fixing bugs, adding new features, improving documentation, or enhancing the user experience, your contributions are highly valuable.

## License

This project is licensed under the [MIT License](LICENSE).
