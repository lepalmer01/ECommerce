# E-Commerce Back End Using ORM

## Description

This project focuses on the back end for an e-commerce site. Leveraging Object-Relational Mapping (ORM) through Sequelize, this application provides a robust Express.js API interface to interact with a MySQL database. This solution caters to internet retail companies seeking to enhance their online presence with the latest technologies for e-commerce platforms.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Contributing](#contributing)
- [Questions](#questions)
- [Credits](#credits)

## Installation

To get started, clone this repository to your local machine. You will need Node.js, MySQL, and npm installed to run this application.

1. Install the necessary npm packages by running `npm install` in the terminal.
2. Ensure you have MySQL installed and running on your machine. Create your database by using the `schema.sql` file found in the `db` folder. Execute this file in your MySQL client to set up your database.
3. Create a `.env` file in the root directory to store your sensitive data, including your MySQL username, password, and database name.

## Usage

To use this application:

1. Populate your database with the provided seed data by running `npm run seed`.
2. Start the server using `npm start`. This will initiate the Express.js API and sync the Sequelize models to the MySQL database.
3. Use a platform like Insomnia to test API routes for creating, retrieving, updating, and deleting data for categories, products, and tags.

## Demonstration

- [Link to Walkthrough Video](<https://drive.google.com/file/d/1mJKEgFT0LItbBpdsk5KlOl8Owy4hQGeB/view?usp=share_link>)

This video demonstrates the functionality of the API, including all acceptance criteria being met.

## Technologies Used

- Node.js
- Express.js
- MySQL
- Sequelize ORM
- dotenv for environment variables

## Features

- Connect to a MySQL database using Sequelize.
- Create, read, update, and delete (CRUD) operations on categories, products, and tags.
- Test API routes using Insomnia.

## Contributing

Contributions are welcome. Please fork the repository and submit a pull request with your updates.

## Questions

If you have any questions or comments about this project, please feel free to contact me.

- [GitHub Profile](https://github.com/lepalmer01)
- [Email](lpalmer@live.com)

## Credits

Thank you for the tips and suggestions from Bootcamp instructors, learning assistants, classmates, and resources. Thank you to my tutor Sara and Rene for insights regarding my code. I have used http://www.stackoverflow.com, and https://chat.openai.com to research information. Lastly,thanks to OpenAI's Chatgpt-4 for help in creating this README.md template.
