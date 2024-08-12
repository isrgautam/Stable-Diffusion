# Stable-Diffusion
Stable Diffusion is a powerful text-to-image and image-to-image model. 
In this model I created an Variation auto encoder which instead like normal auto encoder do not convert image into latent vector but compress the image, it decreases the no of pixels but increases the no of features inside each pixel.
Then we created a U-NET in pipeline.py. Then we created our sampler in ddpm.py file. Clip file contains code to process the prompt.
Eg.
For prompt : A wolf with basketball in basketball court
![Alt text]("C:\Users\srgau\OneDrive\Pictures\Screenshots\Screenshot 2024-08-12 174055.png")

For prompt : A dog with sunglasses on beach
![Alt text]("C:\Users\srgau\OneDrive\Pictures\Screenshots\Screenshot 2024-08-12 174232.png")

