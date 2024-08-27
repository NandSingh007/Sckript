# ReactJS Developer Tasks

## Project Overview

The goal of this project is to develop a dynamic and responsive dashboard page using ReactJS. The dashboard will feature interactive charts and tables to visualize analytical data. The focus is on efficient loading, elegant design, and optimal user experience.

## Features

- **12-Section Grid Layout:** The dashboard is designed using a 3x4 grid layout, providing a structured and organized display of data.
- **Interactive Charts:** The dashboard includes charts to visualize data effectively. Any charting library can be used to implement these charts.
- **Data Tables:** Two sections of the grid are dedicated to displaying data in table format, providing detailed insights.
- **Mock API Integration:** Data for the charts and tables is pulled from a mock API using `react-query`, ensuring efficient and effective data fetching.
- **Grid Components:**
  - **Title:** Each grid section has a descriptive title.
  - **Description:** A brief description of the data or chart displayed.
  - **Chart Area:** The primary area of the grid dedicated to displaying the chart or table.
  - **Reload Option:** A reload button to refresh the data in each grid section.
- **Responsive Design:** The page is fully responsive, with the layout adapting to different screen sizes. Specifically, three charts are visible in the desktop view.

## Technologies Used

- **ReactJS:** The main framework for building the dashboard.
- **React Query:** For efficient data fetching and state management from the mock API.
- **Charting Libraries:** Any charting library of your choice (e.g., Chart.js, Recharts, D3.js) can be used to create interactive charts.
- **CSS/Grid Layout:** For responsive design and grid-based layout.

## Project Structure

```plaintext
.
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── components
│   │   ├── GridSection.js
│   │   ├── Chart.js
│   │   ├── DataTable.js
│   │   └── ...
│   ├── hooks
│   │   └── useFetchData.js
│   ├── pages
│   │   └── Dashboard.js
│   ├── services
│   │   └── api.js
│   ├── App.js
│   ├── index.js
│   └── ...
└── README.md
