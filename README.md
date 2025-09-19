# GenDet for detecting AI Images
These days it can be difficult to differentiate between AI generated images from reality, which are rampant across social media! Inspired by this, here is a manual implementation of the GenDet model, an adversarial teacher-student transformer network designed for detecting AI-generated images. Research Paper found [here](https://arxiv.org/pdf/2312.08880).

## Implement it yourself!!
Use this project as reference to code other models with transformer or adversarial architecure! Doing this project will give you a deeper understanding and appreciation of the transformer architecture and neural netowkrs too!

The Notebook contains handwritten code for the transformer encoder block, self attention mechanism, teacher student architecture and custom loss functions. Make sure to use a Kaggle GPU to generate the CLIP embeddings, as there is significant GPU usage.
Achieved good accuracy at nearly 90% using real and AI generated images from the following datasets: [AI and Human Art Classification](https://www.kaggle.com/datasets/kausthubkannan/ai-and-human-art-classification), [AI recognition dataset](https://www.kaggle.com/datasets/superpotato9/dalle-recognition-dataset) from Kaggle.
