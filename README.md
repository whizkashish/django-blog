**Project Name: Django Blog**

## Overview:
This project aims to provide a simple yet functional blogging application implemented in Python, utilizing SQLite as the database.

## Features:
- User-friendly command-line interface.
- Lightweight SQLite database for data storage.

## Setup Instructions:

### 1. Clone the Repository:
```bash
git clone https://github.com/whizkashish/django-blog.git
cd django-blog
```

### 2. Set up Virtual Environment (Optional but Recommended):
```bash
# Install virtualenv if you haven't already
pip install virtualenv

# Create a virtual environment
virtualenv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate
```

### 3. Install Dependencies:
```bash
pip install -r requirements.txt
```

### 4. Run the Application:
```bash
python manage.py
```

## Usage:
- Upon running the application, follow the prompts to perform CRUD operations on blog posts.
- Use the command-line interface to create, read, update, and delete blog posts as needed.

## Database:
- This application uses SQLite as its database.
- The SQLite database file (`db.sqlite3`) will be created automatically upon running the application for the first time.
- All blog post data will be stored in this SQLite database.

## Dependencies:
- Python 3.x
- SQLite3
- Click (for command-line interface)

## Contributing:
Contributions are welcome! Feel free to open issues or pull requests for any improvements or fixes.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author:
[Kashish]