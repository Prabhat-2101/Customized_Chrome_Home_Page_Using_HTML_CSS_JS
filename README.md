# Customize Chrome Home Page Mini Project

## Overview

This project is a customizable Chrome home page built using HTML, CSS, and JavaScript. It allows users to enter a search query and be redirected to search results related to the query. Additionally, users can download a custom font file (`.ttf`), or the application will default to the browser's compatible font.

## Features

- **Search Query**: Users can enter a search query and get redirected to the search results page.
- **Custom Font**: Option to download and apply a `.ttf` font file (poppins-medium.ttf).
- **Default Font**: If no custom font is provided, the browser's default font will be applied.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling and layout of the application.
- **JavaScript**: Functionality and interactivity of the application.

## Getting Started

### Prerequisites

- A web browser (e.g., Chrome, Firefox, Safari)
- Basic understanding of HTML, CSS, and JavaScript
- Optional: Custom `.ttf` font file

### Installation

1. **Clone the repository** or download the ZIP file.

   ```bash
   git clone https://github.com/Prabhat-2101/Customized_Chrome_Home_Page_Using_HTML_CSS_JS.git
   ```

2. **Navigate to the project directory**.

   ```bash
   cd Customized_Chrome_Home_Page_Using_HTML_CSS_JS
   ```

3. **Download and add the Poppins font file (optional)**: You can download the `Poppins` font from [1001 Fonts](https://www.1001fonts.com/poppins-font.html). Place the `poppins-medium.ttf` file in the project directory.

4. **Open `index.html` in your web browser**.

### File Structure

```
/Customized_Chrome_Home_Page_Using_HTML_CSS_JS
│
├── index.html      # Main HTML file
├── styles.css      # CSS styles for the application
└── poppins-medium.ttf # Poppins font file (optional)
```

## Usage

1. Open the `index.html` file in a web browser.
2. Enter your search query in the input field and press click the search button.
3. The page will redirect to the search results for the entered query.

## Custom Font Integration

To use the `Poppins` font, follow these steps:

1. Download the `Poppins` font from [1001 Fonts](https://www.1001fonts.com/poppins-font.html).
2. Place the `poppins-medium.ttf` font file in the project directory.
3. In `style.css`, include the following CSS to load and apply the `Poppins` font:

   ```css
   @font-face {
     font-family: 'poppins-medium';
     src: url('poppins-medium.ttf') format('truetype');
   }

   body {
     font-family: 'poppins-medium', sans-serif;
   }
   ```

4. If no custom font is provided, the browser will use the default font.

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository and submit a pull request.
