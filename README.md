# Flashy Memorizer

Flashy Memorizer is a lightweight, browser-based application designed for active recall and technical study. This project serves as a personal tool to reinforce learning through digital flashcards, focusing on efficiency and ease of use.

## Project Overview

Flashy Memorizer is a hobby project created to streamline the process of memorizing technical concepts, command-line arguments, and scripting syntax. By providing a clean interface for self-testing, it allows for consistent review of complex material without the overhead of heavy software.

## Architecture and Design

To prioritize portability and ease of access, this project is built using a **single-file architecture**. All logic, styling, and structure are contained within one `index.html` file.

### Why a Single HTML File?

* **Simplicity:** As a hobby project, the goal was to eliminate complex build steps, external dependencies, or web server requirements.
* **Portability:** The entire application can be moved, shared, or backed up as a single document.
* **Performance:** There are no additional network requests for CSS or JavaScript files, resulting in near-instant load times.
* **Zero Configuration:** It runs natively in any modern web browser without needing to install Node.js, Python, or other runtimes.

## Features

* **Internalized Styling:** Responsive CSS is embedded within the file to ensure the layout remains consistent across different screen sizes.
* **Client-Side Logic:** Interactive elements are handled via Vanilla JavaScript, ensuring the application remains functional even without an internet connection.
* **Minimalist UI:** The interface is designed to reduce distractions and focus entirely on the learning material.

## Getting Started

Since this project is a standalone HTML file, there is no installation process required.

### Running on Windows

1. Clone the repository to your local machine:
   ```cmd
   git clone [https://github.com/Maame-codes/Flashy_memorizer.git](https://github.com/Maame-codes/Flashy_memorizer.git)

2. Navigate into the project folder:  cd Flashy_memorizer
 
3. Open the application directly in your default browser using the command line: start index.html

   
**Technical Implementation Details**

For those looking to understand the code, the file is organized into three distinct sections:

The Skeleton (HTML): Defines the containers for the flashcards, navigation buttons, and progress indicators.

The Skin (CSS): Located within <style> tags. It uses Flexbox or Grid for centering content and defines transitions for card-flipping animations.

The Brain (JavaScript): Located within <script> tags. It manages the state of the flashcard deck, handles the "flip" logic, and updates the DOM dynamically based on user interaction.
