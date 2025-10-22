# AI Art Gallery

Welcome to the AI Art Gallery, a modern web application designed to showcase stunning AI-generated artworks. This gallery offers a sleek, responsive user interface, dynamic content loading, and useful features for an enhanced browsing experience.

## Features

*   **Dynamic Content Loading**: Artworks and their metadata are loaded dynamically from `metadata.json`, making it easy to update the gallery content without modifying the HTML.
*   **Light/Dark Theme Toggle**: Users can switch between a light and a dark theme, with their preference persisted in `localStorage` for a consistent experience across sessions.
*   **Search Functionality**: Easily find artworks by typing in the search bar. The gallery filters artworks by both title and creator in real-time.
*   **Responsive Design**: Built with Tailwind CSS, the gallery provides a seamless experience across various devices and screen sizes.
*   **Interactive UI**: Artworks feature subtle hover effects to draw attention.

## Getting Started

To run this project locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd ai-art-gallery
    ```

2.  **Ensure `metadata.json` exists:**
    Place your `metadata.json` file in the root directory of the project, alongside `index.html`. This file should contain an array of artwork objects. Each object should have at least `id`, `title`, `creator`, `imageUrl`, and optionally `description` properties.

    *Example `metadata.json` structure:*
    ```json
    [
      {
        "id": "1",
        "title": "Quantum Dreamscape",
        "creator": "V. K. Aris",
        "imageUrl": "https://picsum.photos/seed/quantum/400/300",
        "description": "A surreal landscape born from quantum fluctuations."
      },
      {
        "id": "2",
        "title": "Neon Future City",
        "creator": "A. L. Tech",
        "imageUrl": "https://picsum.photos/seed/neon/400/300",
        "description": "A vibrant cityscape envisioned for a high-tech future."
      }
    ]
    ```

3.  **Open `index.html`:**
    Simply open the `index.html` file in your preferred web browser. All necessary styles and scripts are self-contained within this single HTML file.

## Redeploying on GitHub Pages

This project is ideal for hosting on GitHub Pages. To update and redeploy:

1.  **Commit your changes:** Make sure all your modifications (including updates to `index.html`, `README.md`, `metadata.json`, etc.) are committed to your repository.
2.  **Push to `main` (or your configured GitHub Pages branch):**
    ```bash
    git push origin main
    ```
3.  GitHub Pages will automatically detect the changes and redeploy your site, making the updated gallery available online shortly after your push.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.