# text_to_image
This code is a complete pipeline for generating an image using a text prompt with the Stable Diffusion v1.5 model, running either on GPU (CUDA) or CPU, and optionally displaying and saving the result.


This code generates an image from a text prompt using the Stable Diffusion v1.5 model. It loads the model, sets generation parameters like prompt, image size, and seed, then uses the pipeline to create an image. The image is displayed using matplotlib and saved locally. It automatically uses GPU if available for faster performance.
