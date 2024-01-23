# Django Blog #

Django Blog is a simple blog application created using Django, a high-level web framework for Python. This application allows users to create and manage blog posts, organize them into categories, and engage in discussions through comments.

## Features ##

1.  Post Management: Users can create and manage blog posts with a title, body, and publication date.

2. Category Organization: Blog posts can be categorized into different categories to better organize and structure the content.

3. Comments: Users can leave comments on individual blog posts, fostering discussion and engagement.

## Installation ##
To run the Django Blog locally, follow these steps:

1. Clone the repository:

        git clone https://github.com/chrispl89/django_blog.git
        cd Django_blog

2. Install dependencies:

        pip install -r requirements.txt

3. Apply migrations

        python manage.py migrate

4. Create a superuser account (optional but recommended for admin access):

        python manage.py createsuperuser

5. Run the development server:

        python manage.py runserver

6. Access the application in your web browser at http://127.0.0.1:8000/.

## Author ##

Krzysztof Jaroński