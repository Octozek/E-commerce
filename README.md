# E-commerce Application

This is a basic e-commerce application built with Node.js, Express.js, Sequelize ORM, and MySQL database.

## Features

- **Product Management**: Browse, view, create, delete, and update products.
- **Category Management**: Create, delete, and update categories for products.
- **Tagging System**: Associate multiple tags with products and manage tags with CRUD operations.
- **RESTful API**: Access and manipulate data through RESTful API endpoints.
- **Sample Data**: Seed the database with sample data for testing and demonstration.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/octozek/e-commerce.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd e-commerce
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

4. **Set up the database**:
   - Create a MySQL database.
   - Update the database connection details in `config/config.json`.

5. **Run migrations to create database tables**:

   ```bash
   npm run migrate
   ```

6. **Seed the database with sample data**:

   ```bash
   npm run seed
   ```

7. **Start the server**:

   ```bash
   npm start
   ```

8. **Access the application**:
   Access the application in your browser at [http://localhost:3001](http://localhost:3001).

## Usage
Use Postman or a similar tool to interact with the provided API endpoints.
Send HTTP requests to perform CRUD operations on products, categories, and tags.
Refer to the API documentation for details on available endpoints and their usage.

![Project Screenshot](img/Screenshot_2024-05-06_122409.png)

## Demo
[Demo Video](https://youtu.be/zByxfRuhTMo)

## Contributing
Contributions are welcome! Please create an issue or submit a pull request if you have any suggestions, feature requests, or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
