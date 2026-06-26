# DUMMYAPI-APITesting
DummyJSON API Testing Project
Project Overview
This project demonstrates manual API testing performed on the DummyJSON public APIs using Postman. The objective of the project was to practice and document real-world QA testing activities including functional testing, negative testing, API validation, response verification, and bug reporting.
The project includes:
•	API test case documentation
•	Postman request collections
•	Postman validation scripts
•	Bug reports
•	Test summary documentation
•	Screenshots and execution evidence
 
Tools Used
•	Postman
•	DummyJSON API
•	Microsoft Excel
•	Microsoft Word
 
APIs Tested
Products API
•	Retrieve all products
•	Validate response structure
•	Validate required fields
•	Validate status codes
Search API
•	Verify keyword search functionality
•	Validate relevance of returned results
Authentication API
•	Validate authentication endpoint behavior
•	Verify API response handling for unavailable endpoint
 
Testing Types Performed
•	Functional Testing
•	Negative Testing
•	Validation Testing
•	Response Verification
•	Basic Security Validation
 
Key Validations Performed
•	Status code verification
•	Required field validation
•	Response body validation
•	Search relevance validation
•	Invalid parameter handling
•	POST request validation
•	Authentication validation
 
Postman Test Scripts
Basic Postman scripts were written using JavaScript to automate response validations such as:
•	Required field existence
•	Search keyword relevance
•	Status code checks
•	Security-related validations
 
Defects Identified
BUG_API_001
Products API accepted invalid negative limit parameter and returned inconsistent product count behavior.
BUG_API_002
Search API returned irrelevant products unrelated to the provided keyword.
BUG_API_003
Authentication API endpoint returned 404 Not Found for valid login request.
 
P## Project Structure

DummyJSON-API-Testing-Project
│
├── README.md
│
├── Reports/
│   ├── DummyAPI.xlsx
│   └── TEST_SUMMARY_REPORT.docx
│
├── Postman/
│   ├── DummyJSON_API_Collection.json
│   └── API_Test_Documentation.docx
│
├── Bug-Reports/
│   ├── BUG_API_001.docx
│   ├── BUG_API_002.docx
│   └── BUG_API_003.docx
│
├── Test-Cases/
│   ├── API_PROD_001.docx
│   ├── API_PROD_002.docx
│   ├── API_PROD_003.docx
│   ├── API_PROD_004.docx
│   ├── API_PROD_005.docx
│   ├── API_PROD_006.docx
│   ├── API_SEARCH_001.docx
│   └── API_AUTH_001.docx
│
└── Screenshots/


 
Key Learnings
•	Learned manual API testing using Postman
•	Practiced GET and POST request testing
•	Developed Postman validation scripts using JavaScript
•	Performed positive and negative testing
•	Created bug reports and QA documentation
•	Improved understanding of API behavior and HTTP status codes
 
Conclusion
This project successfully demonstrates foundational QA and API testing practices including request validation, response verification, defect reporting, and professional test documentation.

