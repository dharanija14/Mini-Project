# Test Plan:
## High Level Test Plan 

|Test ID | Description  | Exp I/P | Exp O/P |  Actual O/P | Type of Test |
|--------|--------------|---------|---------|-------------|--------------|
|H_01 | Add book | 1234,"c programming" | 1 | 1 | Scenario based|
|H_02| View book | 1234,"c programming" | 1 | 1 | Scenario based |
|H_03| Search book | 1234 | 1 | 1| Scenario based |
|H_04 | Update book | 1234,"issued","13/07/2021","30/08/2021","c programming","A",900 | 1| 1| Scenario based |
|H_05| Delete book | 1234 | 1 | 1 | Scenario based |


## Low Level Test Plan 

|Test ID | Description | Exp I/P | Exp O/P | Actual O/P | Type of test |
|--------|-------------|---------|---------|------------|--------------|
|L_01| Add details of new book | 1234,"c programming" | 1 | 1 | Scenario based |
|L_02| View the details of books | 1234,"c programming" | 1| 1| Scenario based |
|L_03| Search the details of book by ID | 1234 | 1| 1| Scenario based |
|L_04| Update the book status | 1234,"issued","13/07/2021","30/08/2021","c programming","A",900 |1 | 1| Scenario based |
|L_05| Delete the book by ID | 1234 |1 |1 | Scenario based |

