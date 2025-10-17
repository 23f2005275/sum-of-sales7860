# Sales Summary Dashboard

This project provides a simple, single-page web application designed to fetch and process sales data from a `data.csv` file. It calculates the total sales from the specified CSV column and displays the sum dynamically on the page, along with a custom title.

## Features

*   **Dynamic Sales Calculation:** Fetches `data.csv`, parses its content, and sums the values in the 'sales' column.
*   **Custom Title:** The page title is dynamically set to `Sales Summary [Your Seed Value]`.
*   **Responsive Design:** Built with Tailwind CSS for a modern, mobile-friendly interface.
*   **Client-Side Data Processing:** All data fetching and processing occur directly in the user's browser using JavaScript.
*   **Simple Setup:** No backend server required; simply open `index.html` in your web browser.

## Setup

To run this application, ensure you have the following files in the same directory:

*   `index.html`: The main application file.
*   `data.csv`: The CSV file containing your sales data, with a column named 'sales'.

Simply open `index.html` in any modern web browser.

## Usage

Upon opening `index.html`, the application will:
1.  Set the page title to `Sales Summary ${seed}`.
2.  Fetch the `data.csv` file.
3.  Parse the CSV to find the 'sales' column.
4.  Calculate the sum of all values in the 'sales' column.
5.  Display the total sales amount prominently on the page.

If there are any issues fetching or parsing the data, an appropriate error message will be displayed.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **JavaScript:** For data fetching, parsing, and dynamic content updates.
*   **Tailwind CSS:** For styling and responsive design.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.