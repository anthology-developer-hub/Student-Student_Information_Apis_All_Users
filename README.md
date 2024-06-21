# Student-StudentInformation_Apis

## Description

This project involves postman collection to fetch the information of  All students,fetch the information based on Student Id and StudentCurrent enrollment by calling student api's in postman.

## Installation

### Postman

To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API List

The `api/postman/StudentInfoPostmanCollection.postman_collection` file contains the following APIs:

- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Students`: Returns all student Information.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Students(studentId)`: Returns a student information based on given Student id.
- `GET https://sisclientweb-700031.campusnexus.cloud/ds/campusnexus/Students/CampusNexus.GetCurrentEnrollmentByStudentId(studentId=6)`: Returns the LTI placement with the   specified Id.

## Usage

After importing the `StudentInfoPostmanCollection.postman_collection` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the collection variables correctly:

- `username`: student environment username
- `password`: student environment password
