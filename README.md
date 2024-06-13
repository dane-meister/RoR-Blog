# Ruby on Rails: Blog 💎

## Description
The blog application is a functional web application built with Ruby on Rails, designed to provide a straightforward platform for users to create, read, update, and delete blog posts (CRUD). Each blog post consists of a title and content, allowing users to share their thoughts, stories, and information. Articles contain comments and both have statuses for public, private and archived. 

The blog application is ideal for anyone looking to quickly set up a personal or small-scale blog. It provides the essential features required to manage blog content without any unnecessary complexity. This makes it an excellent choice for beginners who are new to web development or those who need a simple platform to share their writings.

NOTE: Current authorization credentials are limited to username: "admin" password: "secret"

### Features
- Create Blog Posts: Users can easily create new blog posts by providing a title, content, and optional status (default: public).
- Read Blog Posts: All created blog posts are listed on the homepage, where users can click on individual posts to view the full content.
- Update Blog Posts: Users can edit their existing blog posts to update the title or content as needed.
- Delete Blog Posts: Users can delete posts they no longer want to keep, ensuring the blog stays relevant and up-to-date.
- User-Friendly Interface: The application offers a clean and intuitive interface, making it easy for anyone to navigate and use the blog functionalities.
- Create and Delete Comments: Users can post comments and verifie users can delete comments, ensuring only wanted feedback and opinions on blog posts and no spam.

### Technologies
- Ruby on Rails: A web application framework written in Ruby.
- SQLite3: A lightweight, disk-based database used as the default database in Rails.
- Puma: A web server designed for speed and concurrency.
- Sass: A stylesheet language that is compiled into CSS.
- Webpacker: A tool to manage JavaScript and CSS assets.
- Turbolinks: A JavaScript library that makes navigating a web application - faster.
- jQuery: A fast, small, and feature-rich JavaScript library.

## Prerequisites
- Ruby: Ensure you have Ruby installed (preferably version 3.1 or higher).
- Rails: Install Rails by running gem install rails.
- SQLite3: Make sure SQLite3 is installed on your system.

## Getting Started
### Installation
1. Clone the repository:
     git clone https://github.com/dane-meister/RoR-Blog.git
     cd RoR-Blog
2. Install Dependencies
     bundle install
3. Set up the Database
     rails db:create
     rails db:migrate
4. Start the rails server:
     rails server
5. Visit the application
     Open your web browser and navigate to http://localhost:3000.
#### Contributing 
Note: This project is a simple Ruby on Rails application created following the "Getting Started with Rails" guide (https://guides.rubyonrails.org/getting_started.html). The application is designed to help new Rails developers understand the basics of Rails development, including setting up the development environment, generating a new Rails application, creating a database, and building basic CRUD (Create, Read, Update, Delete) functionality.

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes. 
