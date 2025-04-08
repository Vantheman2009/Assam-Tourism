# Guwahati Tourism Website

## Project Overview
The **Guwahati Tourism** project is a single-page web application designed to showcase the rich cultural, historical, and natural heritage of Guwahati, Assam, India. The project provides an interactive and multilingual platform for users to explore various tourist attractions, including religious sites, educational institutions, natural wonders, food destinations, and historical spots.

## Features
- **Multilingual Support**: The website supports English, Hindi (हिंदी), and Assamese (অসমীয়া), allowing users to switch languages seamlessly via a dropdown menu.
- **Interactive Navigation**: A sticky header provides links to different sections (Religious, Educational, Nature, Food, Historical) with smooth scrolling.
- **Visually Engaging Interface**:
    - Vibrant header with a gradient background.
    - Introductory section with a background image of the Brahmaputra River.
    - Content sections displaying attractions in a responsive grid layout.
    - Uniform image sizing (`object-fit: cover`) for a consistent look.
- **Dynamic Content Rendering**: All text content and image lists are dynamically updated based on the selected language using JavaScript.
- **Image Handling**: If an image file specified in the data is missing, the image element is hidden to avoid displaying broken icons.
- **Categorized Content**: Tourist attractions are categorized for easy browsing.
- **GitHub Pages Deployment**: The website is deployed and accessible via GitHub Pages.

## Technologies Used
- **HTML5**: For structuring the web page.
- **CSS3**: For styling the application, including layout (Flexbox, Grid), responsive design, and visual effects (gradients, transitions).
- **JavaScript (ES6)**: For interactivity (scrolling, language switching) and dynamic content rendering (updating text and images).

## Project Structure
```
.
├── project.html       # The main HTML file containing structure, styles, and scripts
├── resources/         # Directory containing all image assets
│   ├── image1.jpg
│   └── ...
└── README.md          # This file
```

## How to View the Project

### Live Demo (GitHub Pages)
You can view the live version of the website deployed on GitHub Pages:
[https://vantheman2009.github.io/Assam-Tourism/project.html](https://vantheman2009.github.io/Assam-Tourism/project.html)
*(Note: Ensure GitHub Pages is enabled and correctly configured for your repository for this link to work)*

### Running Locally
1.  **Clone the repository** to your local machine:
    ```bash
    git clone https://github.com/Vantheman2009/Assam-Tourism.git
    ```
2.  **Navigate** to the project directory:
    ```bash
    cd Assam-Tourism
    ```
3.  **Open the `project.html` file** in your preferred web browser (e.g., Chrome, Firefox, Safari, Edge). Double-clicking the file usually works.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.
