# Ebook Website

Welcome to the Ebook Website! This project is built using Bootstrap 5 and SASS, designed to provide users with a seamless experience for downloading free e-books. It incorporates modern web design principles and responsive design for optimal viewing across devices.

## Demo
<img src="src/images/screen.png"  />

## Features

- **Modern Layout:** Custom colors, styles, and backgrounds to enhance user experience.
- **Responsive Design:** Ensures the site looks great on desktops, tablets, and mobile devices.
- **Sticky Navbar:** A stylish sticky navigation bar that changes on scroll for easy access.
- **Bootstrap Modals:** User-friendly modals for displaying additional content without navigating away from the page.
- **Form & Input Styles:** Clean and styled forms for user interactions.
- **Testimonials Section:** Showcases user feedback to build trust and engagement.

## Usage

Feel free to explore the website, download free e-books, and interact with the features. You can also modify the styles and contents as needed to make it your own.

## Installation

In order to customize this website, you need to install [Node.js](https://nodejs.org/en/). Then, clone this repository and run:

1. **Clone the repository :**
  ```bash
  git clone https://github.com/yourusername/ebook-website.git
  ```
2. **Navigate to the project directory :**
  ```bash
  cd ebook-website
  ```
3. **Install dependencies :** 
This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass.
  ```bash
  npm install
  ```
4. **Run :**
  ```bash
  npm run compile:sass
  ```

You can add Bootstrap variables to the `bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.

## Technologies Used

- HTML
- CSS (SASS)
- Bootstrap 5
- FontAwesome (installed via npm)

## Contributing

Contributions are welcome! If you have suggestions for improvements or features, please fork the repository and submit a pull request.

## Acknowledgments

This website was developed during the Bootstrap 5 course taught by Brad Traversy. I created this project to enhance my understanding of Bootstrap and SASS. The course offered valuable insights and techniques that significantly shaped my approach to this project.

Special thanks to the Bootstrap team for their robust framework and to the FontAwesome team for providing an impressive icon library that added to the site's visual appeal.
