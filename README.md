# Dec2025Framework

## Java Selenium Maven TestNG Automation Framework - December 2025

A comprehensive automation testing framework built with Java, Selenium WebDriver, Maven, and TestNG for robust and scalable test automation.

## Features

- **Selenium WebDriver**: Industry-standard web automation tool
- **TestNG**: Powerful testing framework with parallel execution support
- **Maven**: Build automation and project management
- **ExtentReports**: Advanced HTML test reporting
- **Page Object Model**: Maintainable test architecture
- **Parallel Execution**: Multi-threaded test execution for faster results
- **Logging**: Comprehensive logging with Log4j

## Project Structure

```
dec2025Framework/
├── src/
│   ├── main/
│   │   ├── java/          # Application code (if needed)
│   │   └── resources/     # Configuration files
│   └── test/
│       ├── java/          # Test classes and page objects
│       └── resources/     # TestNG configuration and test data
├── pom.xml                # Maven configuration
└── README.md              # This file
```

## Prerequisites

- Java 11 or higher
- Maven 3.6.0 or higher
- Git

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/somnathsarak/dec2025Framework.git
   cd dec2025Framework
   ```

2. Install dependencies:
   ```bash
   mvn clean install
   ```

## Running Tests

### Run all tests:
```bash
mvn test
```

### Run specific test class:
```bash
mvn test -Dtest=TestClassName
```

### Run tests in parallel:
Tests are configured to run in parallel by default (2 threads). Modify `src/test/resources/testng.xml` to adjust thread count.

## Dependencies

- Selenium Java 4.15.0
- TestNG 7.8.1
- ExtentReports 5.0.9
- Log4j 2.20.0

## Configuration

Update test configuration in `src/test/resources/testng.xml`

## Reporting

Extent Reports are generated after test execution in the `extent-reports/` directory.

## Contributing

Feel free to fork this project and submit pull requests.

## License

MIT License

## Author

somnathsarak
