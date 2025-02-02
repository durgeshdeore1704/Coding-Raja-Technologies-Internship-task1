# Flask Blogly Application

## Overview

Flask Blogly is a personal web development project that showcases a full-stack blogging platform, intricately crafted using Python's Flask framework and a PostgreSQL database. This project exemplifies my proficiency in developing and integrating both frontend and backend components of a web application.


## Key Features

- **User Profile Creation**: Simple yet effective system allowing users to create and display profiles, demonstrating user interface design and database management skills.
- **Blog Post Management**: Enables users to write, display, and manage blog posts, showcasing the ability to handle dynamic content and database operations.
- **Tags Management**: Enables users to create tags, add tags to posts, and edit tags on posts. This shows my ability to use many to many relationships within SQL.

- **Flask & PostgreSQL Integration**: The application leverages Flask for backend logic and PostgreSQL for data storage, reflecting expertise in key web development technologies.
- **Clean and Responsive UI Design**: The interface is designed to be straightforward and responsive, focusing on user experience and ease of interaction.
- **Efficient Code Structure**: Emphasis on writing clean, structured code, adhering to best practices in software development.

This project is a practical example of creating a user-friendly web application from the ground up, highlighting skills in both frontend design and backend development.


## Installation and Setup

### Prerequisites

- Python (Version 3.6 or later)
- pip (Python package manager)
- PostgreSQL

### Installation Guide

1. **Clone the Repository**


2. **Create a Virtual Environment** (Recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Database**
   - Initialize a PostgreSQL database named `blogly`.
   - Ensure the database URI in `app.py` matches your database configuration.

5. **Optional - set up using random seed data**
   ```bash
   python seed.py
   ```

## Usage

To run the application:

```bash
flask run
```

Then, navigate to `http://localhost:5000` in your browser to use Flask Blogly.



## License

Flask Blogly is released under the MIT License. See the [LICENSE](LICENSE.md) file for more details.

## Contact

For questions or feedback regarding Flask Blogly, please contact me at:

- **Email**: [20220802392@dypiu.ac.in](mailto:20220802392@dypiu.ac.in)
- **GitHub Profile**: [durgeshdeore1704](https://github.com/durgeshdeore1704)


