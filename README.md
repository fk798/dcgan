# dcgan

This project is for CS-UY 3943 Mining Massive Datasets class at NYU Tandon School of Engineering.

This project demonstrates the capabilities of the Deep Convolutional Generative Adversarial Network (DCGAN). 

The file named art.py is a scraper that scrapes images from WikiArt, an encyclopedia containing numerous art images. This file was obtained from Robbie Barrat's genre-scraper.py in his art-DCGAN repo (see references below).

The file named google.py is a scraper that scrapes from Google Images. 
Because of issues with regards to scraping WikiArt, I originally planned to scrape from Google, but seeing that some of the images there were not artworks (some images were advertisements/informative graphics and not artworks), I decided to use a Kaggle dataset that already had a large sample of images from WikiArt (see references below).

The files named landscape.ipynb and portrait.ipynb are Jupyter Notebook files that you can run on your machine to produce your own images using the DCGAN. They are essentially identical in code, with the only difference being that one contains images from the network being trained on a sample of landscape artworks, while the other was trained on a sample of portrait artworks. You can see the progress it made from the start of the training to the end, and the final products for both trainings.

The folder named images_good contains the final products after training the DCGAN - the landscape, and the portrait products.

## References

For references, you can check out the following links:

DCGAN paper - https://arxiv.org/pdf/1511.06434.pdf%5D

Robbie Barrat's Lua implementation - https://github.com/robbiebarrat/art-DCGAN

Pytorch's implementation - https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html

WikiArt Kaggle Dataset - https://www.kaggle.com/ipythonx/wikiart-gangogh-creating-art-gan?select=abstract

WikiArt - https://www.wikiart.org/
