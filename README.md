# E-commerce Platform Automation Testing

## Project Overview
This repository contains the automated testing scripts and configurations for an e-commerce platform, ensuring reliability, performance, and security.

## Technologies and Tools Used
- **Automation Tools:** Selenium, Cucumber
- **API Testing:** REST Assured, Postman
- **Performance Testing:** JMeter
- **Security Testing:** OWASP ZAP
- **CI/CD Integration:** Jenkins
- **Programming Languages:** Java, Python

## Repository Structure
- `automation-scripts/`: Selenium and Cucumber test scripts for end-to-end testing
- `api-testing/`: REST Assured scripts and Postman collections for API testing
- `performance-testing/`: JMeter test plans and results
- `security-testing/`: OWASP ZAP configurations and reports
- `documentation/`: Project documentation and reports
- `Jenkinsfile`: CI/CD pipeline configuration

## Setup Instructions
1. Clone the repository: `git clone https://github.com/shanmugasai-v/ecommerce-platform-automation-testing.git`
2. Navigate to the project directory: `cd ecommerce-platform-automation-testing`
3. Follow the setup instructions in the respective directories to configure and run the tests.

## Usage Guidelines
- To run automated tests: `mvn clean test` (for Maven projects)
- To execute API tests: `newman run api-testing/postman-collection.json`
- To perform performance testing: Open JMeter and load the test plan from `performance-testing/`
- To initiate security tests: Follow the instructions in `security-testing/README.md`
