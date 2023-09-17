# Cheers

## Overview

Welcome to the Cheers application! This project is a web application that allows users to manage their collection of beers. It leverages several technologies and libraries to provide a responsive and user-friendly experience. This README file provides an overview of the application's architecture, technologies used, and key features.

## Technologies Used

The Cheers application is built using the following technologies and libraries:

1. **Vue.js:** This JavaScript framework is at the core of the application, providing the foundation for building interactive user interfaces.

2. **Local Storage:** Local storage is utilized to store and manage the user's beer items, allowing them to persist across sessions.

3. **Axios Middleware:** Axios middleware is employed to connect to APIs and retrieve data from a server, enhancing the application's capabilities to fetch and display beer information.

4. **Bootstrap CSS:** The latest version of Bootstrap CSS is used to style the application, including components such as cards, modals, tooltips, and more, ensuring a modern and appealing user interface.

5. **jQuery and Popper.js:** jQuery and Popper.js are utilized for tooltip functionality, enhancing the user experience with helpful tooltips.

## Responsive Design

The Cheers application is designed to be fully responsive, providing an optimal user experience across various screen sizes. Here's how the responsiveness is implemented:

1. **Medium and Large Screens:** On screens equal to or larger than the medium size, beer items are displayed in two columns, making the most of the available space.

2. **Small Screens:** For screens between small and medium sizes, a single row is displayed to ensure content fits the viewport appropriately.

3. **Inner Components:** Modals, tooltips, and other inner components are also responsive, adapting to different screen sizes seamlessly.

![Small screens](md-sized-screen.gif)
![Medium screens](./md-sized-screen.gif)

## Application Architecture

The Cheers application is organized into different folders within the `src` directory, following a modular and maintainable structure:

1. **src/components:** This directory contains reusable components such as `objectList`, `objectListItem`, and `emptyPane`.

2. **src/views:** The main views of the application are found here. Each view may contain one or more components, and they define the structure of individual pages.

3. **src/utilities:** The `axios` library is stored in this directory, where the API endpoint is defined. This allows the application to interact with a server to retrieve data.

4. **src/router:** The routing logic of the application is managed here, defining routes for each endpoint or page. For instance, the route `/` refers to the home view.

## API Integration

The Cheers application communicates with external APIs by sending requests with parameters like `pageNumber` and `pageSize`. When users click the "Show More" link, the page number is incremented, triggering an API call to fetch additional data.

---

Thank you for exploring the Cheers application! We hope you enjoy managing your beer collection with this responsive and feature-rich web application. If you have any questions or encounter issues, please refer to our documentation or reach out to our support team. Cheers to good times and great beers! 🍻
