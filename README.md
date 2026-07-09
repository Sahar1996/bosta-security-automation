# Bosta Security Automation Assessment

## Overview

This project contains automated security API tests created using Postman and Newman.

## Security Test Cases

- Invalid Authentication Token
- Missing Authorization
- SQL Injection
- Malicious Input Validation
- Invalid OTP
- Email Enumeration

## Tools Used

- Postman
- Newman
- GitHub Actions

## Running the Tests

Run the collection locally using:

```bash
newman run "Bosta Security Automation Assessment.postman_collection.json" -e "Bosta STG.postman_environment.json"
```

## CI/CD

GitHub Actions automatically runs the Newman collection on every push to the `main` branch.
