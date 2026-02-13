# NAIN OPTICALS - Scrollytelling Experience

This is a premium, scroll-driven landing page built with React, Vite, and Framer Motion.

## 🚀 Getting Started

1.  Open this folder in your terminal:
    ```bash
    cd scrolly-site
    ```
2.  Install dependencies (if you haven't yet, though I already ran it):
    ```bash
    npm install
    ```
3.  Run the development server:
    ```bash
    npm run dev
    ```
4.  Open the link shown (usually http://localhost:5173).

## 📁 Asset Management

Currently, the site is running in **Placeholder Mode** because no image assets were found.

To enable the cinematic image sequences, you must place your image files in the `public/assets` folder.

### Directory Structure

The site expects the following folders in `public/assets/`:

-   `hero/` (Projected frame count: 25)
-   `classic/` (25 frames)
-   `bold/` (25 frames)
-   `transparent/` (25 frames)
-   `sunglasses/` (25 frames)
-   `premium/` (25 frames)

### Naming Convention

Inside each folder, images must be named sequentially using 3 digits:

-   `001.jpg`
-   `002.jpg`
-   ...
-   `025.jpg`

### Example
`public/assets/hero/001.jpg` -> Start of Hero animation.

**Note:** If you drop the files in while the server is running, you may need to refresh the page.

## 🛠️ Technology Stack

-   **React + TypeScript**: Core framework.
-   **Vite**: Fast build tool.
-   **Framer Motion**: Text animations and scroll physics.
-   **Canvas API**: High-performance image sequence rendering.
-   **Vanilla CSS**: Premium styling with `Outfit` font.
