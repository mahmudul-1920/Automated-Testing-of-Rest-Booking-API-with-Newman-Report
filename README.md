### Rest Booking API Testing with Postman Newman
This project demonstrates API testing using Postman, providing a collection of tests to validate various endpoints of the API.

### Features
- Tests for GET, POST, PUT, DELETE requests
- Collection of tests covering different API endpoints
- Environment setup for easy switching between environments
- Pre-request scripts for data setup
- Test scripts for assertions and validations

## API Documentation:
- https://documenter.getpostman.com/view/13082503/2sA2xmUAJ1

### Technology used:
- Postman
- Newman
### Prerequisite:
- Node Js
- Newman
- Newman Html Report Library

### Installation
1. Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
2. Clone the repository:
   
git clone https://github.com/mahmudul-1920/Automated-Testing-of-Rest-Booking-API-with-Newman-Report.git

3. Import the Postman collection:
    + pen Postman.
    + Click on the Import button.
    + Select the file from the repository.
4. Import the Postman environment:
    + In Postman, click on the gear icon in the top right corner.
    + Select Import and choose the file.
5. Newman and Report Installation Process:
    + Newman Install Command:
       npm install -g newman
    + Newman Html Report Install Command:
       npm install -g newman-reporter-htmlextra
## Usage
1. Select Environment:
   + In Postman, select the appropriate environment (e.g., Development, Production) from the top-right dropdown.
2. Run Collection:
   + Select the imported collection from the Collections sidebar.
   + Click on the Runner button to open the collection runner.
   + Select the desired environment.
   + Click Start Test to run the collection.
3. View Results:
   + Once the tests are complete, view the results in the Runner tab.
   + Detailed test results can be viewed for each request.
# Testing
