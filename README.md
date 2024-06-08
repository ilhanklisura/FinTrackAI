# eClinica: Online Health Management System

Welcome to eClinica, an Online Health Management System designed to streamline healthcare processes, enhance patient care, and facilitate efficient management of medical records. This web-based application is built using C#, ASP.NET Core, Vue.js, and MSSQL, offering a robust and user-friendly solution for healthcare providers.

## Features

- **Patient Management:** Easily manage patient records, including personal information, medical history, and treatment plans.

- **Appointment Scheduling:** Schedule and track appointments, ensuring a smooth workflow for healthcare professionals and patients.

- **Electronic Health Records (EHR):** Maintain digital health records, enabling quick access to patient data, prescriptions, and test results.

- **Billing and Invoicing:** Simplify the billing process with integrated invoicing features for healthcare services rendered.

- **Prescription Management:** Generate and manage digital prescriptions, improving accuracy and accessibility.

- **User Authentication and Authorization:** Ensure data security with user authentication and role-based authorization.

## Technologies Used

- **Backend:** C#, ASP.NET Core
- **Frontend:** Vue.js
- **Database:** MSSQL

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/ilhanklisura/eclinica.git
   ```

2. Set up the database:

   - Create an MSSQL database and update the connection string in the `appsettings.json` file.

   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=<server>;Database=<database>;User=<user>;Password=<password>;"
   }
   ```

3. Build and run the application:

   ```bash
   dotnet build
   dotnet run
   ```

4. Access the application in your web browser at `http://localhost:5000`.

## Contributing

We welcome contributions from the community! If you'd like to contribute to eClinica, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE.md).

## Support

For any issues or questions, please [open an issue](https://github.com/ilhanklisura/eclinica/issues) on GitHub.

---

Thank you for using eClinica! We hope it serves as a valuable tool in managing healthcare services effectively. If you have any suggestions or feedback, feel free to reach out.
