# African fashion Image Synthesis with Latent Diffusion Model
​
The Inclusive Fashion AI is an initiative of  [Ai4Innov](https://ai4innov1.gitlab.io/ai4innov/), an association committed to create inclusive and diverse AI models for various industries. The Inclusive Fashion AI aims to create datasets and AI models that are much more representative of the diversity that exists in the world of fashion, particularly in African fashion. Because using state-the art generative models (more oriented to western fashion) do not produce results that can reflect all the variety of African fashion, we think useful to fill this gap by providing a model for African fashion Image Synthesis. In this project, we finetune stable diffusion model on a large african fashion images dataset.
The resulting model outputs meaningful results, and could help stylists, designers and broadly people interresing in african fashion to test new ideas and have new inspirations.
​
## Overview
​
The first stage of the project involved collecting a large volume of data of over 96000 images of African fashion. Some of the images were scraped from Pinterest and the rest come from Afrikrea, one of the most known online market places specialized in African fashion, arts and craft. Some preprocessing was applied to enhance their quality. The dataset is open source and serves as training dataset to finetune [stable diffusion model](https://arxiv.org/abs/2112.10752) v1-4.
​
## Data
​
The dataset is available as open source, and can be accessed through [insert link to the dataset here]. None adapted images were removed and a standardized version of prompts has been created to allow the model to learn on the same type of prompts for the different images as the initial prompts did not really reflect the characteristics of the clothes. The standardized prompts take into account the cloths typology, the material, the fabric, the color and the gender who can wear them.
​
## Models
​
The fine-tuned model can generate better images of African fashion. The code used to fine tune and generate these images is also open source, and can be accessed through [insert link to code here]. For inference (and training), you may require at least 30 GB of VRAM.
​
## Contributions
​
We are dedicated to contributing to the AI ecosystem and to creating more inclusive and diverse AI models. We encourage contributions to the project and welcome feedback from the community. If you find any issues with the data or models, please feel free to open an issue on this repository.
​
## Installation
​
[Add installation instructions here]
​
## Usage
​
[Add usage instructions here]
​
## License
​
The data and code for this project are released under the [insert license name here]. By using this data or code, you agree to abide by the terms of this license.
​
## Credits
​
This project was made possible through the work of Ai4Innov and the contributions of [insert names of contributors here].
​
Thanks also to the providers of this repo : https://github.com/huggingface/diffusers/tree/main/examples/text_to_image
---
​
We hope that this project will help to promote more diverse and inclusive AI models for the fashion industry, particularly for African fashion. Thank you for your interest in our project, and we welcome your contributions to this important initiative.
Réduire

