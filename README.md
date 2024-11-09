# SASS Practice Project

This repository is a practice project for learning and implementing SASS (Syntactically Awesome Style Sheets). SASS is a CSS preprocessor that allows for more efficient, manageable, and maintainable styling.

## About the Project

This project includes various exercises to explore the features and capabilities of SASS, including variables, nesting, mixins, inheritance, and more. The goal is to create a strong foundation in SASS to enhance CSS code organization and styling productivity.

### Features

- Using SASS variables for reusable values (e.g., colors, font sizes)
- Nesting selectors to simplify CSS structure
- Creating and using mixins for reusable code snippets
- Leveraging inheritance to reduce redundant styles
- Organizing styles using partials and imports

## Getting Started

### Prerequisites

- **Node.js** (to install SASS via npm)
- Basic knowledge of CSS and HTML

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/sass-practice.git
   ```

2. Navigate to the project directory:

   ```bash
   cd sass-practice
   ```

3. Install SASS:

   ```bash
   npm install -g sass
   ```

4. Compile SASS to CSS:

   ```bash
   sass --watch scss:css
   ```

## Usage

- Edit the `.scss` files in the `scss` directory to practice different SASS features.
- The output CSS files will be generated in the `css` directory.
- Open `index.html` in a browser to view the changes.

## Project Structure

```plaintext
sass-practice/
├── css/                 # Compiled CSS files
├── scss/                # SASS files
│   ├── _variables.scss  # Variables
│   ├── _mixins.scss     # Mixins
│   ├── _base.scss       # Base styles
│   ├── main.scss        # Main SASS file
├── index.html           # HTML file to preview styles
└── README.md            # Project documentation
```
