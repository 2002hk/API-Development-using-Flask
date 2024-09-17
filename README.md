# API-Development-using-Flask

This project is a Flask-based API that provides various endpoints to access IPL-related data. The API allows users to retrieve information about IPL teams, team vs. team statistics, team records, batting records, and bowling records through different endpoints.

## Features

- **Retrieve a list of IPL teams.**
- **Get head-to-head statistics between two IPL teams.**
- **Fetch overall performance records for a specific IPL team.**
- **Retrieve the batting record of a specific player.**
- **Get the bowling record of a specific bowler.**

## Project Structure

- The API uses two custom modules, `ipl` and `ipl2`, which contain the logic for fetching and processing IPL-related data.
- The Flask application exposes several routes (API endpoints) for interacting with the IPL data.

## API Endpoints

### 1. `/api/teams`
- **Method**: `GET`
- **Description**: Fetches a list of all IPL teams.
- **Example**:
  ```bash
  GET http://localhost:5000/api/teams
  ### Sample Response

```json
{
  "teams": ["Mumbai Indians", "Chennai Super Kings", "Royal Challengers Bangalore", ...]
}



