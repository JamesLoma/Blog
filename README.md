
# Blog

Django Blog is a simple and customizable blog application built with Django, a high-level Python web framework. It provides a foundation for creating a feature-rich blog with ease.

## Features

- **User Authentication:** Allow users to register, log in, and manage their profiles.
- **Create, Edit, and Delete Posts:** Easily manage your blog content through CRUD operations.
- **Comment System:** Engage with your audience through a built-in commenting system.
- **Responsive Design:** Ensure a seamless experience across various devices.
- **Tagging:** Categorize your posts with tags for better organization.
- **Search Functionality:** Enable users to search for specific content.
- **Rich Text Editing:** Use Markdown or a WYSIWYG editor for writing posts.

## Getting Started

1. **Clone the repository:**
git clone https://github.com/JamesLoma/django-blog.git


2. **Navigate to the project directory:**

cd blog


3. **Create a virtual environment:**

python -m venv venv


4. **Activate the virtual environment:**

- On Windows:

  ```
  .\venv\Scripts\activate
  ```

- On macOS/Linux:

  ```
  source venv/bin/activate
  ```

5. **Install dependencies:**

pip install -r requirements.txt

6. **Apply migrations:**

python manage.py migrate

7. **Create a superuser (admin):**

python manage.py createsuperuser

8. **Run the development server:**

python manage.py runserver

9. **Open your browser and visit http://127.0.0.1:8000/ to view the blog.**

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue. Feel free to submit pull requests with improvements or new features.

## License
Blog is licensed under the MIT License. Refer to the LICENSE file for detailed information.