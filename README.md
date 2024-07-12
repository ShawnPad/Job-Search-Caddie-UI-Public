# Job-Search-Caddie-UI-Public

Job Search App is a personal job board built with Angular. The application communicates with a backend API built with ASP.NET Core to manage and filter job postings.

![Screenshot 2024-07-12 at 12 50 20 PM](https://github.com/user-attachments/assets/8d863f69-2f6b-46c2-bff7-8eb6fb36bdc5)


## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [API Integration](#api-integration)
- [Development](#development)
- [Building for Production](#building-for-production)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or above)
- [Angular CLI](https://angular.io/cli)
- [ASP.NET Core API](https://github.com/your-username/job-search-api) running and accessible

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/job-search-app.git
    cd job-search-app
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

## Configuration

1. **API Endpoint**:

    Update the API endpoint in `src/environments/environment.ts` to point to your ASP.NET Core API. Example:

    ```typescript
    export const environment = {
      production: false,
      apiUrl: 'http://localhost:8080/api'
    };
    ```

## Running the Application

1. **Start the Angular development server**:

    ```bash
    ng serve
    ```

    The application will be available at `http://localhost:4200`.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Project Structure

- `src/app`: Contains the main application code.
- `src/app/components`: Contains Angular components.
- `src/app/services`: Contains Angular services for API interaction.
- `src/environments`: Contains environment configuration files.

## API Integration

The application uses the `JobService` to interact with the ASP.NET Core API. The service is configured to handle CRUD operations for job postings.


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.4.
