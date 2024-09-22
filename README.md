
# Text-to-Image Generator

This project is a Python-based **Text-to-Image Generator** that utilizes advanced deep learning techniques to convert textual descriptions into images. Leveraging the power of popular libraries, this generator offers an accessible way to create visuals from simple text prompts.

## Libraries Used:
- **Pathlib**: For managing filesystem paths.
- **Tqdm**: To provide a progress bar for iterative processes.
- **Torch**: The core deep learning library for model training and inference.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations and array operations.
- **Diffusers**: Utilized for the Stable Diffusion model to generate images from text prompts.
- **Transformers**: For leveraging transformer models, including setting seeds for reproducibility.
- **Matplotlib**: For visualizing generated images and displaying results.
- **OpenCV**: For additional image processing capabilities.

## Features:
- **Text Prompt Input**: Users can input text descriptions to generate corresponding images.
- **Image Generation**: The model utilizes the Stable Diffusion Pipeline to produce high-quality images.
- **Visualization**: Generated images are displayed using Matplotlib for easy viewing and analysis.

## How to Use:
1. Clone the repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python text_to_image_generator.py
   ```
4. Input your text prompt when prompted and observe the generated image.

## Example Usage:
```python
text_prompt = "A serene landscape with mountains during sunset"
generated_image = generate_image_from_text(text_prompt)
plt.imshow(generated_image)
plt.axis('off')
plt.show()
```

## Future Improvements:
- Enhance the user interface for better interaction.
- Add functionality for saving generated images in various formats.
- Explore additional models and techniques for improved image quality.
- Make an Application
