# API Authentication QA Automation

## Overview

This project demonstrates API testing for authentication using Postman and Newman.

## Tools

* Postman
* Newman
* DummyJSON API

## Features

* Login API testing
* Token extraction and reuse
* Authorized endpoint testing
* Negative test scenarios

## How to Run

1. Import collection into Postman
2. Run requests manually or via Newman
   #### Install Newman
   `npm install -g newman`
   #### Run the test
   `newman run collection/auth_collection.json -e environment/dev_environment.json`

## Author

Iman Hafifi
