# Rental Property Management Application
A full-stack real estate web application built with Angular (Frontend) and .NET Core MVC (Backend). This application allows users to browse, filter, and manage real estate listings while ensuring a seamless user experience with secure authentication, cloud image storage, and database integration.

## Features
- Property Listings – View, filter, and sort real estate properties
- User Authentication – Secure login and registration system
- Property Management – Add, update, and remove listings
- Photo Upload & Editing – Cloudinary integration for image storage
- Filter & Sorting – Search properties based on price, type, and other parameters
- Responsive UI – Optimized for desktop & mobile devices
- API-Driven Architecture – Seamless interaction between frontend & backend

## Tech Stack
### Frontend – Angular
- Components: Navbar, Add-Property, Property-List, Property-Detail, Property-Card, Photo-Editor
- Services: Alertify, Auth, Housing, User Login/Register
- State Management: Environment-based configurations (development & production)
- Data Handling: Properties stored in properties.json
- Filtering & Sorting: Custom Angular Pipes
### Backend – .NET Core MVC
- Database: MSSQL Database with Entity Framework Core
- Cloud Storage: Cloudinary for managing property images
- Security: Authentication & Authorization

## Setup & Installation
### Prerequisites
- Node.js & Angular CLI installed
- .NET SDK installed
- MSSQL 
- Cloudinary Account for image storage

### Frontend Setup (Angular)
```
cd Frontend
npm install
ng serve
```
#### visit: http://localhost:your-angular-port/ 

### Backend Setup (.NET Core API)
```
cd Backend
dotnet restore
dotnet run
```
#### API Runs on: https://localhost:5001/api

