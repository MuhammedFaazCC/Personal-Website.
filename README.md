# Personal-Website.
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Overview
This repository hosts a personal portfolio website designed to showcase an individual's professional profile, projects, and contact information. It serves as a digital resume and a central hub for presenting work and skills to potential employers or collaborators.

## System Architecture
The project employs a client-side architecture, primarily utilizing standard web technologies:
*   `index.html`: The main entry point of the website, defining the overall structure, content, and linking to other resources.
*   `mail.js`: A client-side JavaScript module likely responsible for handling interactive elements, such as form submissions (e.g., a contact form) or dynamic content updates.
*   `assets/`: A directory designated for static resources, including images, fonts, icons, and other media files used throughout the website.

## Prerequisites
To view and interact with this website, the following is required:
*   **Web Browser**: A modern web browser (e.g., Chrome, Firefox, Safari, Edge) capable of rendering HTML5, CSS3, and executing JavaScript.

## Installation
To set up the project locally, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/MuhammedFaazCC/Personal-Website.git
    ```
2.  **Navigate into the project directory**:
    ```bash
    cd Personal-Website.
    ```

## Usage
To access and interact with the personal website:

1.  **Open in a Web Browser**:
    Locate the `index.html` file within the cloned directory and open it directly with your preferred web browser.
    ```bash
    # Example for Linux/macOS
    open index.html

    # Example for Windows (adjust based on default browser)
    start index.html
    ```
2.  **Local Development Server (Optional)**:
    For development purposes or to ensure proper handling of relative paths and AJAX requests (if any), it is recommended to serve the files using a local HTTP server.
    *   **Using Python's `http.server`**:
        ```bash
        python -m http.server 8000
        ```
        Then, open your browser and navigate to `http://localhost:8000`.
    *   **Using Node.js's `serve` package (if installed globally)**:
        ```bash
        npm install -g serve
        serve .
        ```
        Then, open your browser and navigate to the address provided by `serve`.
