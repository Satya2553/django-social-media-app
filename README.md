<h1>Django Social Media App</h1>

This is a Django-based social media application that allows users to create accounts, upload images with captions, like and follow other users, and customize their profile information. This application uses the SQLite database.

<h2>Installation</h2>

To run this application, you'll need Python 3 and Django 3 installed on your system. Once you have those installed, follow these steps:

Clone the repository to your local machine

- Open a terminal window and navigate to the project directory

- Run <strong>'python manage.py migrate'</strong> to apply the database migrations

- Run <b><strong>'python manage.py runserver'</strong></b> to start the development server

- Open your web browser and navigate to http://127.0.0.1:8000/

<h2>Usage</h2>
<h3>Sign Up</h3>
To create an account, click the "Sign Up" link in the top right corner of the screen. Enter a unique username, email address, and password, and then click the "Sign Up" button. If there are any errors in the form, you'll be prompted to correct them.

<h3>Log In</h3>
To log in to your account, click the "Log In" link in the top right corner of the screen. Enter your username and password, and then click the "Log In" button. If your credentials are correct, you'll be redirected to your feed.

<h3>Upload a Post</h3>
To upload a post, click the "Upload" link in the top right corner of the screen. Choose an image file to upload, add a caption if desired, and then click the "Upload" button. Your post will be added to your feed.

<h3>Like a Post</h3>
To like a post, click the heart icon on the post. If you have already liked the post, the heart icon will be filled in. Click the filled-in heart icon to unlike the post.

<h3>Follow a User</h3>
To follow a user, click the "Follow" button on the user's profile page. If you are already following the user, the "Follow" button will change to "Unfollow". Click the "Unfollow" button to stop following the user.

<h3>Customize Your Profile</h3>
To customize your profile, click the "Settings" link in the top right corner of the screen. You can upload a profile picture and add a bio. Click the "Save Changes" button to save your changes.

<h3>Contributing</h3>
If you'd like to contribute to this project, feel free to submit a pull request. Any contributions are welcome!
