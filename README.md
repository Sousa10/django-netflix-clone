# Netflix Clone

This project is a clone of Netflix built using Django. It allows users to browse and stream movies and TV shows, similar to the functionality of Netflix.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- User Authentication: Sign up, log in, and log out.
- Profile Management: Users can create and manage multiple profiles.
- Browse Movies and TV Shows: Browse through various categories.
- Search: Search for movies and TV shows.
- Watchlist: Add movies and TV shows to a personal watchlist.
- Streaming: Stream movies and TV shows.

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/netflix-clone.git
    cd netflix-clone
    ```

2. **Create a virtual environment(using pipenv)**
    ```bash
    pipenv shell
    ```

3. **Install the dependencies**
    ```bash
    pipenv install
    ```

4. **Apply the migrations**
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser**
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server**
    ```bash
    python manage.py runserver
    ```

7. **Visit the application**
    Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage
- **Sign Up**: Create a new account.
- **Log In**: Log into your account.
- **Create Profile**: Create and manage user profiles.
- **Browse**: Browse through the available movies and TV shows.
- **Search**: Use the search functionality to find specific movies or TV shows.
- **Watchlist**: Add movies and TV shows to your personal watchlist.
- **Stream**: Stream movies and TV shows directly from the app.

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.
