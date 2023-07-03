# MeTime
Welcome to Me Time, a unique social media platform that offers a space for free expression and open communication. In this advanced read-me, you will find information about the application, instructions for developers to get it up and running, a guide on how to use the application, and details about any known issues.
# What is Me Time?
Me Time is a social media platform designed to provide users with a safe and non-judgmental space to express themselves freely. It removes the need for traditional usernames, allowing individuals to share their thoughts and ideas without fear of being judged. The application encourages open dialogue and provides a comment section where users can engage in debates and conversations with each other.
# Developer Setup
To get Me Time running on your development environment, follow these steps:
1.	Install XAMPP or an equivalent local development environment.
2.	Launch XAMPP and start the Apache and MySQL services.
3.	Create a new database for Me Time in your preferred database management system (e.g., MySQL, PostgreSQL).
4.	Rename the .env.example file to .env in the project root directory.
5.	Open the .env file and update the following variables:
•	Set this to the name of the database you created for Me Time.
•	DB_USERNAME and DB_PASSWORD: Set these to the username and password for your database.
•	Other environment variables, such as the application URL or mail settings, can be configured as needed.
6.	Open a terminal or command prompt and navigate to the project directory.
7.	Run the following commands in order:
•	composer install (to install the application dependencies)
•	php artisan key:generate (to generate an application key)
•	php artisan migrate (to run the database migrations)
•	php artisan db:seed (to run the database seeds, if any)
8.	Start the development server by running php artisan serve.
Congratulations! Me Time is now set up on your local development environment.

# How to Use Me Time
Using Me Time is simple and intuitive. Here's a brief guide on how to navigate the application:
1.	Open your web browser and visit the URL where Me Time is running.
2.	Sign up for an account by providing the necessary information or log in if you already have an account.
3.	Once logged in, you will be directed to the main feed where you can see posts from other users.
4.	To create a new post, click on the "Create Post" button and compose your message.
5.	Your post will be visible to all users of the application, and they can engage with it by leaving comments.
6.	Explore other users' posts and engage in conversations by leaving comments on their posts.
7.	Use the search functionality to discover specific posts or users.
8.	Customize your profile by adding a profile picture or updating your bio.
9.	Adjust your account settings as desired, such as changing your password or email address.
Enjoy your time on Me Time and have meaningful interactions with other users in a judgment-free environment!
# Known Issues
While we strive to provide a smooth and flawless experience, there are a few known issues in Me Time that you may encounter:
1.	Occasionally, the application may experience slow loading times when there is a high volume of users or posts. We are continuously working to optimize the performance and scalability of the platform.
2.	In rare cases, users may experience difficulties when uploading images or other media files in their posts. Please ensure that your files meet the specified file size and format requirements.
