# Database Test Suite Fix

This repository contains my solution to the Loop Software API & Database assessment.

## Overview

The project included a database test suite with failing tests. I first ran the environment using Docker to reproduce the failures locally. After confirming the issues, I reviewed the test code and queries to identify the causes of the failures.

Once the issues were identified, I updated the tests so that they aligned with the database schema and constraints. After applying those corrections, the full test suite ran successfully.

## Running the Tests

```bash
docker build -t db-test .
docker run --rm db-test
```

All tests should pass.
