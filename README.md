# Puppy Adoption App

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Introduction

Puppy Adoption App is a web application built with React for the frontend and Java with Spring Boot for the backend. The app allows users to view a list of available puppies for adoption, filter and search for puppies based on specific criteria, see detailed information about each puppy, and initiate the adoption process.

## Author

Erwin Del Rosario

## Installation

1. Clone the repository:

git clone https://github.com/Daszkaleid/puppy-adoption-app.git

2. Frontend Setup:

   - Navigate to the `frontend` directory:
     ```
     cd puppy-adoption-app/frontend
     ```

   - Install dependencies:
     ```
     npm install
     ```

3. Backend Setup:

   - Navigate to the `backend` directory:
     ```
     cd puppy-adoption-app/backend
     ```

   - [Optional] If you're using an IDE like IntelliJ, import the project as a Maven project.

## Usage

1. Run the Backend:

   - From the `backend` directory, execute:
     ```
     mvn spring-boot:run
     ```

2. Run the Frontend:

   - From the `frontend` directory, execute:
     ```
     npm start
     ```

3. Open your browser and go to `http://localhost:3000` to access the Puppy Adoption App.

## API Endpoints

- `GET /puppies`: Fetch a list of available puppies for adoption.
- `POST /puppies`: Add a new puppy to the inventory (admin functionality).
- `GET /puppies/{id}`: Retrieve detailed information about a specific puppy.
- `PUT /puppies/{id}`: Update the details of a puppy (admin functionality).
- `DELETE /puppies/{id}`: Remove a puppy from the inventory (admin functionality).

## Contributing

Contributions to Puppy Adoption App are welcome! If you have any bug fixes, new features, or improvements, please open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


