# Django Boilerplate 2024

This repository contains a Django project that serves as a boilerplate for building web applications using Django. Follow the instructions below to set up and run the project on your local machine.

## Requirements

- [Python 3.11](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/)
- [virtualenv](https://virtualenv.pypa.io/en/stable/) (optional but recommended)

## Setup

1. **Clone the repository:**
    ```shell
    git clone https://github.com/saw4future/django-boilerplate-2024.git
    ```

2. **Navigate to the project directory:**
    ```shell
    cd django-boilerplate-2024
    ```

3. **Create a virtual environment (optional but recommended):**
    ```shell
    python -m venv env
    ```

4. **Activate the virtual environment:**
    - **On Windows:**
        ```shell
        env\Scripts\activate
        ```
    - **On macOS/Linux:**
        ```shell
        source env/bin/activate
        ```

5. **Install the project dependencies:**
    ```shell
    pip install -r requirements.txt
    ```

## Running the Project

1. **Set up the database:**
    ```shell
    python manage.py migrate
    ```

2. **Create a superuser (optional):**
    If you want to access the Django admin interface, create a superuser account:
    ```shell
    python manage.py createsuperuser
    ```

3. **Run the development server:**
    ```shell
    python manage.py runserver
    ```

    The server will start running on `http://127.0.0.1:8000/`.

4. **Access the Django admin interface (optional):**
    - Visit `http://127.0.0.1:8000/admin/` and log in with your superuser credentials.

## Contributing

If you'd like to contribute to this project, feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The Django team for creating the Django framework.
- All open-source contributors for their valuable work.

## Contact

For questions or inquiries, please reach out via [email](mailto:saminulislam786@gmail.com).
Md. Saminul Islam, 
Software Engineer, 
E-mail: saminulislam786@gmail.com

Adnan Al Mahdi
Software Engineer, 
E-mail: adnanjohan54@gmail.com
