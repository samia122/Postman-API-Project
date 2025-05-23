# Postman API Automation Project - User Management (CRUD)

This project automates the testing of a **User Management API** using **Postman** and **Newman**. It covers complete CRUD (Create, Read, Update, Delete) operations with status code and response data validation.

---

## Project Summary

This automation project uses the [ReqRes API](https://reqres.in/) to simulate user operations for testing purposes. It verifies:
- User creation
- Fetching user details
- Updating user info
- Deleting a user

All requests include **data validation** and **status code assertions**.

---

## Features

- ✅ Create User (POST)
- ✅ Get All Users (GET)
- ✅ Get Single User (GET)
- ✅ Update User (PUT)
- ✅ Delete User (DELETE)
- ✅ Status Code Validation
- ✅ Response Body Assertions
- ✅ Pre-request & Test Scripts
- ✅ Environment variables for flexibility
- ✅ HTML report generation using Newman

---

## Folder Structure

user-crud.postman_collection.json # Collection file
dev.postman_environment.json # Environment file
UserCRUD_Report.html # Sample HTML report (generated by Newman)

## Tools Used

- [Postman](https://www.postman.com/)
- [Newman](https://www.npmjs.com/package/newman)
- [Newman HTML Reporter](https://www.npmjs.com/package/newman-reporter-html)
- ReqRes (mock API)
