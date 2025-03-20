# Optimized API Integration for Web Applications

## Overview
This project provides an optimized API integration for web applications using Python and Flask. It efficiently fetches and posts data from/to an external API, handling errors properly.

## Features
- Fetch data from an external API
- Post data to an external API
- Error handling for API failures
- Lightweight and fast integration

## Technologies Used
- **Python**
- **Flask**
- **REST APIs**
- **Requests Library**

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/optimized-api-integration.git
   cd optimized-api-integration
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   python app.py
   ```

## API Endpoints
### 1. Fetch Data
**Endpoint:** `GET /fetch`
- Fetches data from the external API.
- Example response:
  ```json
  [{ "id": 1, "title": "Sample Post" }, { "id": 2, "title": "Another Post" }]
  ```

### 2. Post Data
**Endpoint:** `POST /post`
- Posts JSON data to the external API.
- Example request:
  ```json
  { "title": "New Post", "body": "This is a test post." }
  ```
- Example response:
  ```json
  { "id": 101, "title": "New Post", "body": "This is a test post." }
  ```

## License
This project is licensed under the MIT License.

