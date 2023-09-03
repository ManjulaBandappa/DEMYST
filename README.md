# DEMYST
# Loan Application Backend

This repository contains the backend code for a simple loan application system. The backend integrates with third-party providers, including a decision engine and accounting software providers.

## Project Structure

- `LoanApplicationServer.java`: The main Java file that implements the loan application server.
- `Dockerfile`: Dockerfile for containerizing the application.
- `README.md`: This documentation file.

## Usage

To use this backend application, follow these steps:

1. Clone the repository to your local machine.

```bash
git clone https://github.com/yourusername/loan-application-backend.git

Build the Docker container (ensure you have Docker installed).
docker build -t loan-backend .

Run the Docker container.
docker run -p 8080:8080 loan-backend

Access the application through your web browser or make API requests to the specified endpoints.
Endpoints
/initiate-application: Initiates the loan application.
/business-details: Sets business details.
/balance-sheet: Fetches balance sheet data.
/review-details: Retrieves application data for review.
/submit-application: Submits the loan application.

Dependencies
This project depends on the openjdk:11-jre-slim Docker image for the Java runtime.

