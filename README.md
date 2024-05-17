**URL Shortener**
**Overview**
This Python and Flask-based URL shortener project provides a simple yet effective solution for shortening long URLs into shorter, more manageable links. The application allows users to submit long URLs, generates unique short URLs for them, and stores the mappings in a database. It utilizes Flask for web development and SQLAlchemy for database management.

**DSA Strategies Used**
**1. Hashing:** Hash tables (dictionaries) are used to store mappings between long URLs and their corresponding short URLs efficiently. This allows for fast lookup and retrieval of mappings during URL redirection.

**2. Unique Short URL Generation:** To ensure uniqueness of short URLs, a custom algorithm is employed to generate random or sequential short codes. This algorithm utilizes data structures such as sets or databases to check for collisions and ensure uniqueness of generated short URLs.

**Features**
1. hortens long URLs into compact, easy-to-share short URLs.
2. Allows users to submit long URLs via a user-friendly web interface.
3. Generates unique short URLs using a customizable algorithm.
4. Stores URL mappings in a database for efficient retrieval and management.

**Usage**
1. Installation - Clone the repository or download the source code.
2. Ensure you have Python installed on your system (version 3.x).
3. To start the URL shortener web application, run the following command:
     python app.py
4. By default, the application will run on http://localhost:5000.
