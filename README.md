# Fix-It-Now-Web-Application
FixItNow is a gig economy platform where users can book service providers for various tasks. Similar to Urban Company, FixItNow offers a wide range of service providers that users can book according to their preferred time. The platform provides an attractive user interface built with React.js and utilizes Node.js for backend functionality. MySQL is used for database management, and MUI is incorporated for enhanced UI design (Full-stack web application).

## Features
- **User Booking**: Users can browse and book service providers for their required tasks.
- **Service Provider Registration**: Service providers can register their profiles for inclusion on the platform.
- **Admin Verification**: Profiles undergo admin verification before being displayed on the site.
- **Attractive UI**: The platform features an attractive user interface to enhance user experience.

## Technologies Used
- React.js
- Node.js
- MySQL
- MUI (Material-UI)

## Installation
1. **Clone the repository** to your local machine using the following command:

    ```bash
    git clone git@github.com:YourUsername/Fix-It-Now-Web-Application.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd FixItNow
    ```

3. **Install dependencies** using npm:

    ```bash
    npm install
    ```

4. **Set up the database**:
   - Ensure you have MySQL installed and running on your local machine.
   - Create a database for the project:

    ```sql
    CREATE DATABASE fixitnow_db;
    ```

   - Update the database configuration in the backend code, typically found in a configuration file like `config.js` or `.env`:

    ```env
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=yourpassword
    DB_NAME=fixitnow_db
    ```

5. **Run database migrations** to set up the necessary tables:

    ```bash
    npm run migrate
    ```

6. **Start the backend server**:

    ```bash
    npm run server
    ```

7. **Start the frontend development server**:

    ```bash
    npm start
    ```

8. **Access the application**:
   - Open your web browser and navigate to `http://localhost:3000` to use the FixItNow platform.


## Usage
1. Register as a service provider or user on the platform.
2. Browse available service providers and their services.
3. Book a service provider according to your preferred time slot.
4. Manage bookings and profiles as necessary.

## Contributing
We welcome contributions from the community. Please follow our [contribution guidelines](CONTRIBUTING.md) for details on how to contribute to FixItNow.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
