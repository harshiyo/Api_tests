[![Build](https://github.com/harshiyo/api_tests/actions/workflows/test.yml/badge.svg)](https://github.com/harshiyo/api_tests/actions/workflows/test.yml) 
[![Language: Java](https://img.shields.io/badge/Language-Javascript-orange.svg)](https://github.com/harshiyo/api_tests)


# API Test Collection with Newman Reports

This repository contains API tests for a specific API endpoint, designed to be run using [Postman](https://www.postman.com/) and [Newman](https://github.com/postmanlabs/newman), the command-line collection runner for Postman.

## Getting Started

1. Install [Node.js](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/get-npm) on your machine.
2. Clone this repository to your local machine.
3. In the terminal, navigate to the repository folder and run the following command to install the required dependencies:

```bash
npm install
``` 

4. Run the following command to execute the API tests:

```bash
npm test
``` 

5. The test results will be generated in the `newman` folder in the form of a HTML report.
