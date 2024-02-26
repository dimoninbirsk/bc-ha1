# Resume Service

 This project focuses on collecting resumes from various sources like APIs, web scraping, or PDF files, storing this data in a PostgreSQL database, and then converting the collected data into standardized resumes for the company.

## Project Structure

The project is divided into two main components:

1. **Frontend**:
   - The frontend is responsible for providing a user interface to interact with the system. It allows users to input sources for resume collection, view collected data, and access the standardized resumes.

2. **Backend:
   - The backend handles the business logic of gathering resumes from different sources, storing the data in the PostgreSQL database, and converting the data into standardized resumes.

## Technologies Used

- **Frontend**:
  - Next JS  - framework.
  - Redux Toolkit - state manager.
  - Ant Design - web-page design.

- **Backend**:
  - ASP.NET Core - framework.
  - Entity Framework - interaction with the database.

- **Database**:
  - PostgreSQL.

## Getting Started

### Prerequisites 

Before getting started with the project, ensure you have the following installed: 
- **Node.js**
- **PostgreSQL**
### Run locally

To get started with the frontend, follow these steps:

1. Clone the frontend repository to your local machine.
2. Install the necessary dependencies for the frontend with and run:
```
nom install
npm run dev
```
3. Open web-page on localhost:3000

To get started with the backend, follow these steps:
1. Set up the PostgreSQL database and configure the connection in the backend.
2. Clone the backend repository to your local machine.
3. In *appsettings.json* replace the string **Connection** with your own
4. Create a database schema using migration by writing following code"" in the console:
```
dotnet ef database update
```
5. Install the necessary dependencies for the frontend with and run:
```
dotnet build
dotnet run
```

## Additional Notes

- The project consists of 2 private repositories for the front-end and back-end.
