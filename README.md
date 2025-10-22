# NiftyInvest Stock Dashboard

A professional, responsive stock dashboard for tracking NiftyInvest stocks with real-time data visualization. This project provides an interactive table view of stock data, including search, sorting, and pagination features.

## Design Choices

- **Static Web Application**: Built using  HTML, CSS, and JavaScript for simplicity and ease of deployment without requiring a backend server.
- **Responsive Design**: Utilizes CSS media queries to ensure the dashboard works well on both desktop and mobile devices.
- **User Experience Enhancements**: Includes a fullscreen loader, skeleton loading animation, and fade-in effects to improve perceived performance and visual appeal.
- **Data Handling**: Stock data is loaded from a local JSON file (`stocks.json`) for demonstration purposes. In a real-world scenario, this could be replaced with API calls to fetch live data.
- **Interactivity**: Features include real-time search filtering, sortable table columns, and pagination to handle large datasets efficiently.
- **Styling**: Employs a clean, modern design with a blue color scheme, using CSS animations and transitions for smooth interactions.

## Steps to Run the Project

1. **Clone or Download the Project**: Ensure the  folder containing `index.html`, `script.js`, `styles.css`, and `stocks.json` is in your desired directory.

2. **Open the Application**: Open `index.html` in any modern web browser (e.g., Chrome, Firefox, Safari).

3. **Interact with the Dashboard**:
   - The page will display a loading screen followed by a skeleton loader.
   - After loading, the stock table will appear with data from `stocks.json`.
   - Use the search bar to filter stocks by symbol or company name.
   - Click on table headers to sort columns.
   - Navigate through pages using the pagination controls.

No additional setup or dependencies are required, as this is a client-side only application.
