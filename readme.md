# Flatdango Movie Theater Web Application

Flatdango is a web application that allows users to purchase movie tickets from the Flatiron Movie Theater. This README provides an overview of the project, installation instructions, features implemented, and optional enhancements.

## live link
https://flatdagomovies.netlify.app

## Engineer

Elvis Amonde (https://nyanja1.github.io/my-project/)

## Table of Contents

- [Introduction](#introduction)
- [Project Setup](#project-setup)
- [Features](#features)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Flatdango is a mini web application built using JavaScript. It fetches movie data from a local JSON server and allows users to view movie details, buy tickets, and interact with a menu of available movies.

## Project Setup

To set up the project locally, follow these steps:

1. Clone the repository from GitHub (private repository link).
2. Navigate to the project directory.
3. Open the terminal and install dependencies using npm:

   ```
   npm install
   ```

4. Start the JSON server that serves movie data:

   ```
   npm run server
   ```

5. Open `index.html` in your web browser to view the application.

## Features

### Core Features Implemented:

- **View Movie Details:** Display details such as poster, title, runtime, showtime, and available tickets for the first movie on page load.
- **List of Movies:** Show a menu of all movies on the left side of the page.
- **Buy Ticket:** Decrease available tickets and indicate when a movie is sold out.

## Usage

- Upon loading the page, you will see details of the first movie in the list.
- Click on different movies in the menu to view their details.
- Click "Buy Ticket" to purchase a ticket. Available tickets will decrease.
- (Optional) Delete movies or update ticket sales if extra bonus features are implemented.

## Technologies Used

- HTML, CSS, JavaScript
- JSON Server (for local data storage)
- Fetch API (for making HTTP requests)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/feature-name`).
6. Create a new Pull Request.

## Jibambee!
