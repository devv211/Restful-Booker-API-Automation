# Restful Booker API Automation

## Overview

API Automation Framework built using:

- Postman
- JavaScript
- Newman
- HTML Reports

## APIs Covered

### Positive Flow

- Create Token
- Create Booking
- Get Booking
- Update Booking
- Verify Update
- Delete Booking
- Verify Deletion

### Negative Flow

- Invalid Booking ID
- Unauthorized Update
- Unauthorized Delete
- Missing Mandatory Fields
- Invalid Data Types

## Features

- Dynamic Data Generation
- Environment Variables
- Request Chaining
- Automated Assertions
- Newman CLI Execution
- HTML Reporting

## Execution

```bash
newman run RestfulBooker.postman_collection.json ^
-e RestfulBookerEnvironment.postman_environment.json ^
-r cli,htmlextra
```

## Results

- Total Requests: 15
- Total Assertions: 50
- Failed Tests: 0