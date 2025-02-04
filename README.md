# number_classification API
## Overview
The Number Classification API is built with FastAPI and provides a set of mathematical properties for a given integer. It classifies numbers as prime, perfect, and Armstrong, and computes additional properties such as even/odd status, digit sum, and a fun fact for each number.it was was designed to take a number and returm intresting mathematical properties about it, along with a fun fact.
This API was created for the HNG DevOps Stage 1 task. feel free to contribute.
## Features
- Prime check: Determines if the number is prime.
- Perfect number check: Checks if the number is a perfect number (sum of its divisors equals the number).
- Armstrong number check: Identifies Armstrong numbers (sum of digits raised to the power of the number of digits equals the number).
- Even/Odd classification: Classifies the number as even or odd.
- Digit sum: Computes the sum of digits of the number.
- Fun fact: Returns a fun fact based on the number's classification.
## Endpoint
### Classify Number
Classifies a given number and provides its mathematical properties such as prime, perfect, Armstrong, even/odd, digit sum, and a fun fact.

**Endpoint**: _GET /api/classify-number_
**Query Parameters**:
**number (integer)**: The number to classify. Must be a positive integer.

### Response
<img width="712" alt="Screenshot 2025-02-04 at 21 38 52" src="https://github.com/user-attachments/assets/e2fad011-8574-4f27-9a94-f5be873f51f5" />

### Request
<img width="634" alt="Screenshot 2025-02-04 at 21 44 24" src="https://github.com/user-attachments/assets/cc033977-82c9-4c29-b2f1-dc5ab493cc47" />

## How it works
The API provides a classification of a number based on the following properties:

- Prime: A number is prime if it is greater than 1 and divisible only by 1 and itself.
- Perfect: A perfect number is a positive integer that is equal to the sum of its proper divisors.
- Armstrong: An Armstrong number is one that is equal to the sum of its digits each raised to the power of the number of digits in the number.
- Even/Odd: The number is classified as even if divisible by 2, otherwise it is odd.
- Digit Sum: The sum of all the digits of the number.
- Additionally, a fun fact about the number is provided based on the classification.
