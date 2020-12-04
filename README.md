# IS211-FinalProjectBlog
IS211 Final Project

This application utilizes Flask, SQLAlchemy, and Bootstrap to allow users to create their own unique account with their own image, username, email, and password to create blog posts.  They also have the ability to edit or delete posts as well as update their account information with email or username changes.  It also uses flask_Bcrypt for password hashing and flask_LoginManager to avoid account conflicts.  

The site.db holds the SQL data for the blog and consists of these catagories: user_id, username, email, image_file, password, post_id, title, date_posted, and content.

The project also uses an __init__.py file to maintain file directories as packages.  This allows the import of multiple modules to happen throughout the application logic without circular import errors.  

The account creation function works well but if you would like to log into the blog using an existing account:
username: admin
password: password
