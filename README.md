# Ruby on Rails Sample App (Hartl Tutorial)

This is a sample Ruby on Rails application created as part of the [Michael Hartl's Rails Tutorial](https://www.railstutorial.org/). It's designed to help you learn and understand the fundamentals of building web applications with Ruby on Rails.

## Features

- User authentication (signup, login, logout)
- User profiles
- Micropost creation and deletion
- Following and followers
- Static pages (Home, Help, About, Contact)

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- Ruby: 3.1.2
- Rails: 7.0.4 

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/brolinr/sample_app.git
   ```
2. Navigate to the project's directory:
  ```bash
  cd sample_app
  ```
3. Install required gems:
  ```bash
  bundle config set --local without 'production' && bundle install
  ```
4. Setup the database:
  ```bash
  rails db:migrate
  ```
5. Run the tests:
  ```bash
  rails test
  ```
6. If all tests are passing then start the server:
  ```bash
  rails server
  ```
7. Open your web browser and visit `http://localhost:3000` to access the Rails Tutorial sample app.

### Usage
This app is an implementation of the sample app described in Michael Hartl's Rails Tutorial. You can use it to learn the basics of Ruby on Rails, including user authentication, microposts, and more. Follow the chapters of the tutorial to explore different features.

### License
This project is based on the [https://www.railstutorial.org/](Ruby on Rails Tutorial) by Michael Hartl. Please refer to the tutorial for licensing details and terms of use.

### Acknowledgments
- Michael Hartl for the Rails Tutorial

### Contact
If you have any questions or need assistance with this sample app, please refer to the Ruby on Rails Tutorial for support and additional resources.
Enjoy learning with the Ruby on Rails Sample App! Happy coding!


