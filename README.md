A Python script leveraging the CLIP model (from OpenAI) to classify images based on textual prompts. This project demonstrates how to use the CLIPModel and CLIPProcessor from the transformers library to identify objects in images fetched from URLs. Features include:
- Loading and preprocessing images from the web with custom User-Agent headers.
- Classifying images against a set of predefined text prompts (e.g., "a photo of a cat", "a photo of a dog" etc).
- Displaying results with probabilities and best-match labels using matplotlib.
- Error handling for invalid URLs or non-image content.
