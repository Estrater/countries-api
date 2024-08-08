# Country Names API

This is a simple API that returns a list of 20 country names, created using `json-server`.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Example Response](#example-response)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, you'll need to have Node.js installed on your machine. Then, follow these steps:

1. Install `json-server` globally:

    ```bash
    npm install -g json-server
    ```

2. Clone this repository or create a `db.json` file with the following content:

    ```json
    {
      "countries": [
        { "id": 1, "name": "Brazil" },
        { "id": 2, "name": "Canada" },
        { "id": 3, "name": "Australia" },
        { "id": 4, "name": "Germany" },
        { "id": 5, "name": "India" },
        { "id": 6, "name": "Japan" },
        { "id": 7, "name": "Mexico" },
        { "id": 8, "name": "Nigeria" },
        { "id": 9, "name": "South Africa" },
        { "id": 10, "name": "United Kingdom" },
        { "id": 11, "name": "United States" },
        { "id": 12, "name": "Argentina" },
        { "id": 13, "name": "China" },
        { "id": 14, "name": "Egypt" },
        { "id": 15, "name": "France" },
        { "id": 16, "name": "Italy" },
        { "id": 17, "name": "Russia" },
        { "id": 18, "name": "Saudi Arabia" },
        { "id": 19, "name": "South Korea" },
        { "id": 20, "name": "Spain" }
      ]
    }
    ```

3. Start the `json-server` with the `db.json` file:

    ```bash
    json-server --watch db.json --port 3000
    ```

## Usage

After starting the server, the API will be accessible at `http://localhost:3000/countries`.

You can make a GET request to this endpoint to retrieve the list of countries.

## API Endpoints

- **GET** `/countries` - Returns a list of 20 country names.

## Example Response

```json
[
  { "id": 1, "name": "Brazil" },
  { "id": 2, "name": "Canada" },
  { "id": 3, "name": "Australia" },
  { "id": 4, "name": "Germany" },
  { "id": 5, "name": "India" },
  { "id": 6, "name": "Japan" },
  { "id": 7, "name": "Mexico" },
  { "id": 8, "name": "Nigeria" },
  { "id": 9, "name": "South Africa" },
  { "id": 10, "name": "United Kingdom" },
  { "id": 11, "name": "United States" },
  { "id": 12, "name": "Argentina" },
  { "id": 13, "name": "China" },
  { "id": 14, "name": "Egypt" },
  { "id": 15, "name": "France" },
  { "id
