# Online Shopping Center

This project is a simple static website for an online shopping center, featuring a login page and product listings for three smartphones: iPhone 15, Samsung S25, and Google Pixel 8. The website is built using HTML and includes basic navigation and product details.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [File Structure](#file-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [GitHub Pages](#github-pages)

## Project Overview

The Online Shopping Center is a front-end-only website designed to simulate an e-commerce platform. Users can navigate from a login page to a products page and view detailed information about each product, including images, descriptions, prices, availability, and reviews.

## Features

- **Login Page**: A simple form for users to input their username and password (non-functional, for demonstration purposes).
- **Products Page**: Lists three products with links to their respective detail pages.
- **Product Detail Pages**: Each product (iPhone 15, Samsung S25, Google Pixel 8) has a dedicated page with an image, description, price, availability, and customer reviews.
- **Navigation**: Consistent navigation bar across all pages for easy access to the login and products pages.
- **Responsive Design**: Basic meta viewport settings for mobile compatibility.

## File Structure

```plaintext
Online-Shopping-Center/
├── Docs/                 
│   ├── Page1.html          # Login page
│   ├── Page2.html          # Products listing page
│   ├── Iphone15.html       # iPhone 15 product details
│   ├── SamsungS25.html     # Samsung S25 product details
│   ├── GooglePixel8.html   # Google Pixel 8 product details
│   ├── Images/             # Folder for product images 
│   │   ├── iphone15.jpg
│   │   ├── SamsungS25.webp
│   │   └── GooglePixel8.jpg
└──  README.md              # Project documentation
```

## Setup and Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/HasanMansoor89/Online-Shopping-Center
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Online-Shopping-Center
   ```

3. **Add Images**:

   - Create an `Images` folder in the docs directory.
   - Place the required image files (`iphone15.jpg`, `SamsungS25.webp`, `GooglePixel8.jpg`) in the `Images` folder.

4. **Open the Website**:

   - Open `index.html` in a web browser to view the login page.
   - Alternatively, use a local server (e.g., via VS Code Live Server or Python's HTTP server) for better functionality:

     ```bash
     python -m http.server 8000
     ```

   - Access the website at `http://localhost:8000`.

## Usage

- Start at `index.html` to view the login page.
- Click the "Submit" button to navigate to `Page2.html`, which lists available products.
- Click on any product link to view detailed information on the respective product page (`Iphone15.html`, `SamsungS25.html`, or `GooglePixel8.html`).
- Use the navigation bar to return to the login page or products page.

**Note**: The login form is non-functional and serves as a placeholder. Image paths assume the `Images` folder is in the docs directory.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please ensure your code follows basic HTML standards and includes appropriate comments.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## GitHub Pages

[\[Link to the live site on GitHub Pages\]](https://hasanmansoor89.github.io/Online-Shopping-Center/)
