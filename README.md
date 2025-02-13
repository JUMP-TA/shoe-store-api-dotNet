# Online Shoe Store API

## Overview
The Online Shoe Store API is a lightweight, RESTful web service designed to support basic ecommerce functionality for an online shoe store. It allows users to browse available shoes, retrieve product details, manage a shopping cart, and place orders.

## Project Structure
```
OnlineShoeStoreAPI
├── OnlineShoeStoreAPI
│   ├── Controllers
│   │   └── ShoesController.cs
│   ├── Models
│   │   ├── Shoe.cs
│   │   └── Cart.cs
│   ├── Services
│   │   └── ShoeService.cs
│   ├── OnlineShoeStoreAPI.csproj
│   └── Program.cs
├── OnlineShoeStoreAPI.sln
└── README.md
```

## Setup Instructions
1. Clone the repository to your local machine.
2. Navigate to the `OnlineShoeStoreAPI` directory.
3. Restore the project dependencies using the command:
   ```
   dotnet restore
   ```
4. Run the application using the command:
   ```
   dotnet run
   ```

## API Usage
### Endpoints
- **List All Shoes**
  - **Endpoint:** `GET /shoes`
  - **Description:** Retrieves a list of available shoes.

- **Get Shoe Details**
  - **Endpoint:** `GET /shoes/{id}`
  - **Description:** Retrieves details of a specific shoe by ID.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.