# BDIA-Project
## GANs for medical imaging

![Screenshot](diagram.png)

Dataset: https://ceb.nlm.nih.gov/repositories/malaria-datasets/

### Steps to run
- Run 'Parasitized_images_GAN.ipynb' to create synthetic parasitized images.
- Run 'Uninfected_images_GAN.ipynb' to create synthetic uinfected images.
- Synthetic data is automatically saved into zip files 'Parasitized.zip' and 'Uninfected.zip'.
- Unzip these files into the respective directories.
- Run 'testing_synthetic_images.ipynb' to predict synthetic images on our pretrained CNN model.
