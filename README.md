# PQE Technical Test
Welcome to the Product Quality Engineer technical test!

**IMPORTANT**: if you're here for the Software Development Engineer in Test/QA Automation Engineer position, this repo represents half of the test. The second part can be found [here](https://github.com/CMProductions/sdet-technical-test). 
It is not required, but if you want to, you can automate task #3. Language and framework choice is free (we use Postman, Js, Java and Golang).

## Task 1 - Exploratory testing & bug reporting
Your first task is to find a bug on any website on the internet and create a bug report out of it. The more severe the bug the better, the more famous the site the better. No worries, there’s a ton of bugs out there waiting for you!


## Task 2 - Software analysis
You have 10 minutes to test a release of Whatsapp before it hits production, what would you test? You have the following devices to test: Android, iOS and Desktop.


## Task 3 - API testing & test case generation
Here you'll find a REST API:
https://developers.giphy.com/docs/api/endpoint#search

This is a sample call to retrieve a list of GIFs:
http://api.giphy.com/v1/gifs/search?q=funny+dog&api_key=dc6zaTOxFJmzC

Your third task is to extensively test that API endpoint. You can use the provided *api_key*: it’s a public key for testing out that API. Please, read the documentation before starting.

Provide a list of test cases (minimum 10, maximum 20), covering both functional and non-functional, listing the actual parameters used to execute your test cases (you can use a test matrix). Try to cover as many features and edge cases as possible: this endpoint allows a lot of parameter combinations.

## Deliverable
Please, provide a set of documents/GitHub repo/cloud folder with the solutions to the tasks.

Good luck!
