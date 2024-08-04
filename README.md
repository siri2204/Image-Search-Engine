# Image Search Engine

A simple web application that allows users to search for images using the Unsplash API. This project demonstrates how to fetch and display images from Unsplash based on user input.

## Features

- Search for images using keywords.
- Display a grid of images with links to their Unsplash pages.
- Load more images with a "Show More" button.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Navigate to the project directory:

  ```bash
   cd <project-directory>

3. Open index.html in your web browser.

## Configuration

To use the Unsplash API, you need to replace config.UNSPLASH_ACCESS_KEY with your Unsplash API access key.

1. Sign up for an Unsplash API key at Unsplash Developers.

2. Replace const accessKey = config.UNSPLASH_ACCESS_KEY; in the JavaScript file with your actual access key, for example:
  ```bash
  const accessKey = "YOUR_ACCESS_KEY";

##Usage

1. Enter a keyword in the search box and press Enter or click the search button.
2. View the search results displayed as a grid of images.
3. Click on any image to open its Unsplash page in a new tab.
4. Click the "Show More" button to load additional images.
