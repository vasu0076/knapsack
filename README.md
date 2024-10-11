# Knapsack Website

Welcome to the Knapsack website! This project showcases a simple web application built using Node.js for the backend and HTML/CSS for the frontend. It provides a responsive user interface for managing and visualizing items in a knapsack while also illustrating the classic Knapsack problem.

## What is the Knapsack Problem?

The Knapsack problem is a well-known optimization problem that involves selecting a subset of items, each with a weight and a value, to maximize total value without exceeding a given weight limit. It's commonly used in resource allocation scenarios.

### Example

Imagine you have the following items:

| Item   | Weight | Value |
| ------ | ------ | ----- |
| Item 1 | 1 kg   | $10   |
| Item 2 | 2 kg   | $15   |
| Item 3 | 3 kg   | $40   |
| Item 4 | 5 kg   | $30   |

If your knapsack can hold 5 kg, the optimal selection would be Item 2 and Item 3, providing a total value of $55 while staying within the weight limit.

## Features

- **Dynamic Item Management**: Add, remove, and view items in your knapsack.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- **Knapsack Problem Visualization**: Illustrate how selected items contribute to the optimal solution.
- **Easy to Set Up**: Simple installation and startup process.

## Technologies Used

- **Backend**: Node.js, Express, Body-Parser
- **Frontend**: HTML, CSS

## Installation

To get started with the Knapsack website, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd knapsack-website
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Create a _.env_ file:**

   In the root directory of the project, create a file named `.env` and add the following line to set the port:

   ```bash
   PORT=3000
   ```

4. Start the server:
   ```bash
   node index.js
   ```
5. Open your browser: Navigate to `http://localhost:3000` to view the website.

## Usage

Once the server is running, you can:

Add items to your knapsack.
View all items currently in your knapsack.
Remove items as needed.
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

Express - Fast, unopinionated, minimalist web framework for Node.js.
Body-Parser - Node.js body parsing middleware.
Enjoy using the Knapsack website!
