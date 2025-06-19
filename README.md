# ComicAnimAI

Welcome to ComicAnimAI, an open-source project that transforms static manga pages into dynamic animations using AI! This tool segments comic panels, converts images to videos, adds subtitles, and synthesizes voice-overs—all customizable with your input.

## Project Overview
- **Goal**: Create an AI-driven pipeline to animate manga, making reading more immersive and fun.
- **Features**:
  - Automatic panel segmentation using OpenCV.
  - Image-to-video (img2vid) generation with Stable Diffusion.
  - Chinese subtitle and voice synthesis using VITS.
  - Gradio UI for interactive use and customization.
- **Dataset**: Includes a sample `comic_dataset` with folders like `one_piece_1149`, `one_piece_1150`, and `one_piece_1151`, containing numbered images (0 for cover, 1 for page 1, etc.).

## Current Progress
- Developed a working Jupyter Notebook (`comic_to_video.ipynb`) integrating all core features.
- Sample dataset prepared for testing with One Piece chapters 1149-1151.
- Gradio interface ready for real-time interaction.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ComicAnimAI.git


## Future Plans
Enhance panel segmentation accuracy with deep learning models.
Support longer video generation with optimized memory usage.
Expand dataset with community contributions.
Add manual panel adjustment and more voice options.

## Contribution
Feel free to fork, star, and contribute! Upload your own manga datasets or suggest features. Let's make manga animation accessible to all!
