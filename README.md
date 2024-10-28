# Template Portfolio

:flags: A simplified portfolio template for beginners learning HTML and CSS, with a dash of Aussie humor!

## Features

:pushpin: Basic  
:pushpin: Black and White Design  
:pushpin: Easy to Understand  
:pushpin: Beginner Friendly  
:pushpin: Simple Structure  
:pushpin: Audio Feature  

## Table of Contents

- [Prerequisites](#prerequisites)
- [How to Use](#how-to-use)
- [HTML Structure](#html-structure)
- [CSS Styling](#css-styling)
- [Editing Sections](#editing-sections)
- [Getting Started](#getting-started)

### Prerequisites

You will need the following:

- A web browser
- Basic understanding of HTML and CSS (or at least a good sense of humor!)

## How to Use

1. **Clone the Repository**: 
   Open your terminal and run:
   ```bash
   git clone https://github.com/Hong-Kong-International-School/template-portfolio-website.git
   cd template-portfolio-website
   ```

2. **Open the Project**: 
   Open the `index.html` file in your code editor, right-click on it, and select "Open with Live Server" to view the portfolio in your web browser. Grab a cold one while you’re at it!

## HTML Structure

The HTML file (`index.html`) contains the basic structure of the portfolio. Here are the key sections:

- **Navigation**: 
  ```html
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>
  ```

- **Home Section**: 
  ```html
  <section id="home">
    <h1>G’day Mate! Welcome to Me Portfolio</h1>
    <p>How’s it going? I’m just a newbie having a crack at HTML and CSS, so don’t judge too harshly!</p>
  </section>
  ```

- **Projects Section**: 
  ```html
  <section id="projects">
    <h2>My Fair Dinkum Projects</h2>
    <div class="project">
      <h3>Project 1</h3>
      <p>A ripper of a project description, if I do say so meself!</p>
    </div>
  </section>
  ```

- **About Section**: 
  ```html
  <section id="about">
    <h2>About Me</h2>
    <p>I’m on a mission to conquer web development, and this is my first crack at a portfolio. Not too shabby, eh?</p>
  </section>
  ```

- **Footer**: 
  ```html
  <footer>
    <p>© 2024 Template Portfolio by Rexan Wong - Cheers, mate!</p>
  </footer>
  ```

## CSS Styling

The CSS file (`styles.css`) provides basic styling for the portfolio. Here are the key styles:

- **Body Styles**: 
  ```css
  body {
    font-family: Arial, sans-serif;
    color: black;
    background-color: white;
    margin: 0;
    padding: 0;
  }
  ```

- **Navigation Styles**: 
  ```css
  nav {
    background-color: black;
    color: white;
    padding: 10px;
  }
  ```

- **Section Styles**: 
  ```css
  section {
    padding: 20px;
    border-bottom: 1px solid black;
  }
  ```

- **Footer Styles**: 
  ```css
  footer {
    text-align: center;
    padding: 10px;
    background-color: black;
    color: white;
  }
  ```

## Editing Sections

To customize your portfolio, you can edit the following sections in `index.html`:

- **Home Section**: Change the welcome message and introduction to something that tickles your fancy.
- **Projects Section**: Add your projects by copying the project template. Make it a real showstopper!
- **About Section**: Update your bio and information to reflect your unique self.

### Example of Editing the Home Section

To change the name in the Home section, find this line:

```html
<h1>G’day Mate! Welcome to Me Portfolio</h1>
```
And replace it with your name (or a nickname if you’re feeling cheeky).

### Example of Adding a Project

To add a new project, copy the project template:

```html
<div class="project">
  <h3>Your Project Title</h3>
  <p>Your project description.</p>
</div>
```
This simplified portfolio template is designed to help beginners learn the basics of HTML and CSS while providing a clean and straightforward layout. Feel free to customize it as you learn and have a laugh along the way!