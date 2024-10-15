# WebAPI-NTier-Architecture

This project demonstrates the implementation of a layered architecture using ASP.NET Core Web API. It follows a clean and maintainable design pattern, separating concerns into distinct layers such as Service, Repository, and Entity. Each layer handles specific responsibilities, ensuring scalability, testability, and ease of future modifications.



Read the full article here: [WebAPI : Layered Architecture Design (NTier)](https://serkanyasr.medium.com/webapi-katmanl%C4%B1-mimari-tasar%C4%B1m%C4%B1-ntier-cc03f194f587)




## Getting Started

This guide explains how to set up and run the project on your local machine.

### Prerequisites

- [Visual Studio](https://visualstudio.microsoft.com/) (2019 or later)
- .NET Framework (4.7.2 or later)
- SQL Server (LocalDB or full version)
- EntityFrameWork (6.0.35) 

### Installation

1. **Clone the repository:**

    ```sh
    $ https://github.com/serkanyasr/WebAPI-NTier-Architecture.git
    $ cd WebAPI-NTier-Architecture
    ```

2. **Open the project in Visual Studio:**

    - Open the `WebAPI.sln` file in the WebAPI folder with Visual Studio.


4. **Configure the database connection:**

    - Update the connection string in the `appsettings.json` file with your database details.

    ```sh
    "ConnectionStrings": {
        "SqlConnection": "Data Source=(localdb)\\MSSQLLocalDB;
        Initial Catalog=DbNtier;Integrated Security=True"
    }
    ```



5. **Apply database migrations:**

    - Open the Package Manager Console (Tools > NuGet Package Manager > Package Manager Console).
    - Run the following command to update the database:

    ```sh
    Update-Database
    ```

## Usage

1. **Start the application:**

    - Press F5 or click the "Start" button to run the project.


## Contributing

We welcome contributions! Please open an issue first to discuss what you would like to change before submitting a pull request.

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature-name`)
3. **Commit** your changes (`git commit -m 'Add some feature'`)
4. **Push** to the branch (`git push origin feature-name`)
5. **Open** a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please contact us at: [yasarserkan016@gmail.com](mailto:yasarserkan016@gmail.com)
