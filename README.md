# SSO Archive Project

An Angular web application created to archive, browse, and manage SSO (Star Stable Online) related data.

The application provides an organized interface for browsing horse breeds, viewing detailed breed information and coat variations, and exploring collectible locations through an interactive map.

The project was built using **Angular CLI 21.1.4** and a PHP/MySQL backend API.

## Features

* Browse and search horse breeds
* Live breed search
* Detailed horse breed information
* View different coat variations
* Interactive collectible map
* Filter collectibles by type
* Responsive user interface
* REST-style PHP API integration
* MySQL database integration
* Deployed frontend application

## Technologies

### Frontend

* Angular 21
* TypeScript
* HTML5
* CSS3
* Tailwind CSS

### Backend

* PHP
* MySQL
* REST-style API
* JSON

### Tools & Services

* Git
* GitHub
* Angular CLI
* npm
* Vercel
* InfinityFree

## Project Structure

The project follows a standard Angular application structure:

```text
src/
├── app/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── ...
├── assets/
├── styles.css
└── main.ts
```

The backend API is hosted separately and communicates with the Angular frontend using HTTP requests.

## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/Fabi04/ssoarchive-project.git
cd ssoarchive-project
```

### 2. Install dependencies

Make sure Node.js and npm are installed on your system.

```bash
npm install
```

### 3. Start the development server

```bash
ng serve
```

Once the server is running, open:

```text
http://localhost:4200/
```

## Key Commands

### Start development server

```bash
ng serve
```

### Build the project

```bash
ng build
```

The production build will be generated in the `dist/` directory.

### Run tests

```bash
ng test
```

## API

The Angular application communicates with a PHP backend API to retrieve data from the database.

The API provides data such as:

* Horse breeds
* Breed descriptions
* Breed requirements
* Locations
* Prices
* Coat variations
* Collectible locations

The API returns data in **JSON format**, which is consumed by the Angular frontend.

## Collectible Map

The application includes an interactive map for displaying collectible locations.

Users can:

* Navigate around the map
* Zoom in and out
* View collectible markers
* Filter collectibles by type
* Locate collectibles based on their coordinates

Supported collectible categories include:

* Stars
* Tokens
* Spiders

## Search

The horse archive includes a search functionality that allows users to find horse breeds by name.

The search is implemented on the Angular frontend and communicates with the backend API to retrieve matching results.

## Screenshots

Screenshots of the application can be added here to demonstrate the main features.

### Horse Archive

*Add screenshot here.*

### Horse Details

*Add screenshot here.*

### Collectible Map

*Add screenshot here.*

## What I Learned

Through this project I gained practical experience with:

* Building applications with Angular
* Working with TypeScript
* Creating reusable Angular components
* Communicating with backend APIs
* Working with PHP and MySQL
* Handling JSON data
* Implementing search and filtering functionality
* Working with coordinates and interactive maps
* Deploying a frontend application
* Using Git and GitHub for version control
* Debugging frontend and backend integration issues

## Future Improvements

Possible future improvements include:

* User authentication
* Admin panel for managing archive data
* More advanced filtering
* Improved mobile experience
* Additional collectible categories
* Improved API security
* Pagination for larger datasets
* More comprehensive automated testing

## Author

**Csernák Fábián**

GitHub:
https://github.com/Fabi04

---

## License

This project was created as a personal development project and learning exercise.
