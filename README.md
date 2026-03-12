# CRM Agencia KS

## Documentation

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Elielson214/CRM-Agencia-KS.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CRM-Agencia-KS
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Usage
To start the application, run:
```bash
npm start
```

### API Endpoints
#### 1. Create User
- **POST** `/api/users`
- **Request Body:**
    ```json
    {
      "name": "String",
      "email": "String",
      "password": "String"
    }
    ```

#### 2. Get User
- **GET** `/api/users/:id`
- **Description:** Retrieve a user by ID.

#### 3. Update User
- **PUT** `/api/users/:id`
- **Request Body:**
    ```json
    {
      "name": "String",
      "email": "String"
    }
    ```

#### 4. Delete User
- **DELETE** `/api/users/:id`

### Features
- User authentication and authorization
- RESTful API for user management
- Built with Express and Node.js

## License
This project is licensed under the MIT License.