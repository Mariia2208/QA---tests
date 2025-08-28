# Test Cases: User Age Field (EP + BVA)

## Equivalence Partitioning (EP)
| ID  | Title             | Steps                    | Expected Result                  |
|-----|------------------|-----------------------------|----------------------------------|
| TC1 | Age < 18         | Enter 10 → Submit           | Error: "Age must be ≥ 18"        |
| TC2 | Age between 18-60| Enter 30 → Submit           | Form submitted successfully      |
| TC3 | Age > 60         | Enter 75 → Submit           | Error: "Age must be ≤ 60"        |

## Boundary Value Analysis (BVA)
| ID  | Title             | Steps                       | Expected Result                  |
|-----|------------------|-----------------------------|----------------------------------|
| TC4 | Age = 17         | Enter 17 → Submit           | Error message                    |
| TC5 | Age = 18         | Enter 18 → Submit           | Form submitted successfully      |
| TC6 | Age = 19         | Enter 19 → Submit           | Form submitted successfully      |
| TC7 | Age = 59         | Enter 59 → Submit           | Form submitted successfully      |
| TC8 | Age = 60         | Enter 60 → Submit           | Form submitted successfully      |
| TC9 | Age = 61         | Enter 61 → Submit           | Error message                    |