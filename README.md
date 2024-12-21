# Request Header Parser Microservice

This is a solution to the [Request Header Parser Microservice](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/request-header-parser-microservice) challenge from freeCodeCamp's Back End Development and APIs certification.

## Features

- Provides a `GET` endpoint at `/api/whoami` to parse request headers and return user information.
- Extracts the following details from the request headers:
  - **IP address** (`ipaddress`)
  - **Preferred language** (`language`)
  - **Software (User Agent)** (`software`)

## Example Usage

```bash
GET /api/whoami
```

## Example Output

```bash
{
  "ipaddress": "192.168.1.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"
}
```

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/ashangunatilake/Request-Header-Parser-Microservice.git
```

2. Navigate to the project directory:
```bash
cd Request-Header-Parser-Microservice
```

3. Install dependencies:
```bash
npm install
```

4. Start the server:
```bash
npm start
```
