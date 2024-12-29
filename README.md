# Dicoding Node.js Consume Data

![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-green) ![License](https://img.shields.io/badge/license-MIT-brightgreen)

This project demonstrates how to consume and process data in a Node.js application. It includes examples of fetching data from external APIs, handling JSON responses, and processing data for practical use cases. This project is part of the Dicoding "Belajar Membuat Aplikasi Back-End untuk Pemula" course.

---

## Features

- Fetch data from external APIs using `http` and `https` modules
- Parse and process JSON data
- Understand and handle asynchronous operations
- Display processed data in the application

---

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14.x or later)
- [npm](https://www.npmjs.com/) (v6.x or later)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yorizpra/dicoding_nodejs-consume-data.git
   ```

2. Navigate to the project directory:
   ```bash
   cd dicoding_nodejs-consume-data
   ```

3. Install dependencies (if applicable):
   ```bash
   npm install
   ```

---

## Running the Application

1. Start the application:
   ```bash
   node app.js
   ```

2. The application will fetch and display data from external sources.

---

## Example Usage

### Fetching Data

The application fetches data from a sample API and processes the results. Example endpoint:

- **API URL**: `https://jsonplaceholder.typicode.com/posts`

### Data Display

- Outputs data to the console.
- Demonstrates how to filter, sort, or transform fetched data.

---

## Project Structure

```
├── src
│   ├── fetcher.js          # Handles HTTP requests
│   ├── processor.js        # Processes and formats fetched data
│   ├── app.js              # Main application file
├── data                    # Optional local data for testing
├── package.json            # Project metadata and dependencies
└── README.md               # Project documentation
```

---

## Dependencies

No external dependencies are required for this project. It uses Node.js built-in modules such as `http` and `https`.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Dicoding](https://www.dicoding.com/) for providing the learning platform.
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) for the sample API used in this project.

---

Feel free to contribute to this project by submitting issues or pull requests!
