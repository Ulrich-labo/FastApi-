# FastAPI Web Application for Articles

This is a full-featured web application built with **FastAPI** that allows users to publish articles, follow authors, like, share, and comment on articles. Users can also search for articles or authors using keywords, and share posts on platforms like **Facebook** and **X (Twitter)**. The frontend is designed with **Bootstrap** for an enhanced user experience.

## Key Features:
- **Publish Articles**: Users can write and publish articles.
- **User Interactions**: Like, comment on, and share articles across social platforms like Facebook and X.
- **Subscription System**: Follow authors and see a list of your followers.
- **Search Functionality**: Search for articles or authors using keywords.
- **Article Interaction**: Like, share, and comment on articles of interest.
- **User Dashboard**: View articles from authors you follow.
- **Responsive Design**: The frontend is built using **Bootstrap** to ensure a modern, responsive UI.

## Technologies Used:
- **Backend**: FastAPI
- **Templating**: Jinja2
- **Database**: SQLAlchemy (for database management)
- **Authentication**: fastapi-login, bcrypt, passlib (for secure password handling)
- **Mailing**: fastapi-mail (for sending notifications)
- **File Uploads**: python-multipart (to handle article images or attachments)
- **Frontend**: HTML, CSS, Bootstrap for styling and responsiveness
- **Server**: Uvicorn (for running the FastAPI application)

## Requirements:
- Python 3.10+
- FastAPI
- Jinja2
- SQLAlchemy
- Uvicorn
- fastapi-mail
- fastapi-login
- passlib
- python-multipart
- bcrypt

You can install all dependencies via the `requirements.txt` file:

```bash
pip install -r requirements.txt
  ```
## Running the Application:
Clone the repository:

```bash
git clone  https://github.com/Ulrich-labo/FastApi-.git
```
Navigate to the project directory:

Install dependencies:

```bash

pip install -r requirements.txt
```
Start the FastAPI application using Uvicorn:

```bash
uvicorn main:app --reload
```
Access the application by navigating to http://127.0.0.1:8000 in your web browser.

## Database Configuration:
The application uses SQLAlchemy to manage the database. Be sure to configure the database connection string in the .env or configuration file as needed.
## Features in Detail:
1. Article Publishing:
Users can create, edit, and delete their own articles, with a rich text editor to format their content. Articles can include multimedia attachments like images.

2. Following Authors:
Users can follow other authors to receive notifications of their latest posts in their personal dashboard.

3. Search Articles:
Users can search for articles or authors by entering relevant keywords. This search functionality provides quick access to content matching the user’s interests.

4. Sharing & Liking:
Articles can be liked by other users and shared on external platforms such as Facebook and X (Twitter) with one click.

5. Comments:
Readers can leave comments on articles, fostering interaction and community discussion around various topics.

6. User Profiles:
Authors and readers have personalized profiles where their published articles, subscriptions, and liked posts are displayed.
