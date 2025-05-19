# TESTONE Code Base

## Overview
TESTONE is a sample Java project demonstrating basic application structure and integration with SailPoint IIQ rules. It includes example Java code and configuration for identity management automation.

## Structure
- `src/main/java/` - Java source code (e.g., App.java)
- `config/Rule/` - SailPoint IIQ rule definitions (e.g., FetchCorrelatedEmployees.xml)

## Setup
1. Clone the repository.
2. Build the Java project using your preferred build tool (e.g., Maven or Gradle).
3. Review and configure SailPoint IIQ rules as needed in `config/Rule/`.

## Usage
- Run the Java application:
  ```sh
  java -cp target/classes App
  ```
- SailPoint IIQ rules can be imported into your IIQ environment for identity management automation.

## Example
The provided `App.java` prints a greeting and the first 10 Fibonacci numbers. The `FetchCorrelatedEmployees.xml` rule fetches employees based on the `userType` attribute in SailPoint IIQ.

## Contributing
Feel free to submit issues or pull requests for improvements.

## License
Specify your license here.
