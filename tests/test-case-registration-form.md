### Fields: Name, Email, Password, Age, Submit button

| ID   | Title                          | Preconditions             | Steps                                         | Expected Result                        |
|------|--------------------------------|---------------------------|-----------------------------------------------|----------------------------------------|
| TC01 | Valid registration             | Registration page open    | Enter valid Name, Email, Password, Age=25, Click Submit | Form submitted successfully            |
| TC02 | Empty Name                     | Registration page open    | Leave Name empty, fill other fields, Click Submit | Error: "Name is required"              |
| TC03 | Invalid Email                  | Registration page open    | Enter invalid email, fill other fields, Click Submit | Error: "Invalid email format"          |
| TC04 | Empty Email                    | Registration page open    | Leave Email empty, fill other fields, Click Submit | Error: "Email is required"             |
| TC05 | Password too short             | Registration page open    | Enter password = 3 chars, fill other fields, Click Submit | Error: "Password too short"            |
| TC06 | Age below minimum              | Registration page open    | Enter Age = 15, fill other fields, Click Submit | Error: "Age must be ≥ 18"              |
| TC07 | Age above maximum              | Registration page open    | Enter Age = 65, fill other fields, Click Submit | Error: "Age must be ≤ 60"              |
| TC08 | Submit with all fields empty   | Registration page open    | Click Submit without filling anything         | Errors for all required fields         |
| TC09 | Password at min boundary       | Registration page open    | Enter password = 6 chars, fill other fields, Click Submit | Form submitted successfully            |
| TC10 | Age at boundary values         | Registration page open    | Enter Age = 18 and Age = 60 separately, fill other fields, Click Submit | Form submitted successfully            |
