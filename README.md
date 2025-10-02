# Infinity Castle Durga Puja - A Virtual Durga Puja Experience

An immersive 3D virtual Durga Puja pandal created with Three.js, inspired by the concept of a surreal and endless "Infinity Castle". Explore a procedurally generated world of floating structures, connecting stairways, and atmospheric lighting.

**[Live Demo](https://helplessThor.github.io/infinity_castle_durgapuja/index.html)** 


## About The Project

This project is a WebGL-based virtual pandal that leverages `three.js` to create a vast, atmospheric environment. It procedurally generates a complex world, offering a unique experience for every visit. The scene is designed to be an immersive first-person exploration of a surreal and endless festive space, centered around a beautifully lit idol stage.

## Features

-   **Procedurally Generated World**: The pandal's structure is generated randomly, creating a unique "Infinity Castle" layout every time.
-   **Immersive Controls**: Navigate the world with standard first-person controls (WASD for movement, mouse to look).
-   **Atmospheric Lighting**: The scene uses a combination of ambient, hemisphere, directional, and point lights, along with fog, to create a warm and mystical atmosphere.
-   **Central Idol Stage**: A detailed main stage featuring the Durga idol, complete with its own dedicated lighting.
-   **Custom Textures**: The tatami floor and shoji-style screens use textures dynamically generated with the HTML5 Canvas API.
-   **Dynamic Background**: The world is enveloped in a 360° background created from the `assets/background.avif` image, processed with a vignette effect for added depth.

## Getting Started

To run this project locally, you need a local web server because it uses ES modules (`import`).

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/helplessThor/infinity_castle_durgapuja.git
    cd infinity-pandal
    ```
2.  **Serve the project:**
    You can use any simple local web server. If you have Node.js installed, you can use `http-server`:
    ```sh
    npx http-server .
    ```
    Alternatively, you can use the **Live Server** extension in Visual Studio Code.

3.  **Open in your browser:**
    Navigate to the local address provided by your server (e.g., `http://localhost:8080`).

## Controls

-   **Click**: Lock the pointer to enter the experience.
-   **WASD**: Move forward, left, backward, and right.
-   **Mouse**: Look around the environment.
-   **ESC**: Unlock the pointer and show the instructions menu.

## File Structure

-   `index.html`: The main file containing all the HTML, CSS, and JavaScript code.
-   `assets/`: Contains image assets used in the project.
    -   `idol.png`: The image of the Durga idol.
    -   `background.avif`: The 360° image used for the scene's background.
-   `bkps/`: Contains backup versions of the `index.html` file.
