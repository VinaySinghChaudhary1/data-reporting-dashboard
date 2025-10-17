# Sales Summary Card Application

This project provides a simple, single-file web application demonstrating a responsive 'Summary Card' for sales data. It calculates and prominently displays 'Total Sales' using internally simulated data and is styled with Tailwind CSS.

## Features

*   **Responsive Design**: Adapts beautifully to various screen sizes using Tailwind CSS utility classes.
*   **Summary Card**: A dedicated card (`#summary-card`) to showcase key sales metrics.
*   **Total Sales Calculation**: Dynamically calculates the sum of sales figures from a simulated dataset.
*   **Professional Styling**: Leverages Tailwind CSS for a clean, modern, and professional look with shadows, rounded corners, and appropriate padding.
*   **Single-File Application**: All HTML, CSS (via CDN), and JavaScript are contained within a single `index.html` file for easy deployment and sharing.

## How to Run

To run this application, simply follow these steps:

1.  **Save the `index.html` file**: Save the provided `index.html` content into a file named `index.html` on your local machine.
2.  **Open in Browser**: Open the `index.html` file using any modern web browser (e.g., Chrome, Firefox, Safari).

The application will load, calculate the total sales from its internal dataset, and display the summary card.

## Simulated Data

Although the project context mentioned a `sales_data.csv` file, this single-file web application *simulates* the loading of a CSV. The sales data is hardcoded directly within the JavaScript section of `index.html` as an array of objects. This allows the application to function entirely client-side without needing a server to read a physical CSV file.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: For all styling and responsive design (included via CDN).
*   **JavaScript**: For data simulation, calculation, and dynamic content updates.

## License

This project is licensed under the MIT License. See the `LICENSE` file for full details.
