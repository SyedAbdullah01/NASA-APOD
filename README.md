# NASA APOD (Astronomy Picture of the Day)

![NASA Logo](https://s2.googleusercontent.com/s2/favicons?domain=www.nasa.gov)

NASA APOD is a web application that allows users to explore the Astronomy Picture of the Day provided by NASA's API. Users can view stunning images, read explanations, and save their favorite images for later.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)

## Getting Started

To run this project locally or deploy it, follow these simple steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/SyedAbdullah01/nasa-apod.git
   
   1. Open the project directory:
       cd nasa-apod
   
   2. Create an API key from NASA's API Portal and replace 'API_KEY' in script.js with your actual API key:
       const apiKey = 'YOUR_API_KEY_HERE';
   
   3. Open index.html in your web browser or set up a local server to serve the HTML file.
   

## Usage
- Once you have the project set up, you can use it to explore NASA's Astronomy Picture of the Day:

- The main page displays a loader while fetching data from NASA's API.

- Click on "Load More" to fetch and display the latest NASA images.

- Click on the "Add To Favourites" button to save your favorite images. They will appear in the "Favourites" section.

- You can also remove images from your favorites by clicking the "Remove Favourite" button.

## Features

- Fetch and display NASA's Astronomy Picture of the Day.

- Save your favorite images for later.

- Explore detailed explanations of each image.

- Responsive design for various screen sizes.
