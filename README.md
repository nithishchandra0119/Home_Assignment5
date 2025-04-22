# Home_Assignment5 
Id:700767159
Gangarapu Nithish Chandra

QUESTION 3 (Basic GAN Implementation)
This Programming details the implementation of a basic Generative Adversarial Network (GAN) for generating handwritten digits from the MNIST dataset using [PyTorch/TensorFlow]. The project involved designing two neural networks: a Generator, which learns to create realistic-looking fake digits from random noise, and a Discriminator, which learns to distinguish between real MNIST digits and the Generator's fakes.

The training process involved an adversarial loop where the Generator tries to fool the Discriminator, and the Discriminator tries to correctly identify real and fake images. The video showcases the evolution of the generated digits at different training stages: Epoch 0 (initial random noise), Epoch 50 (early, blurry shapes), and Epoch 100 (more defined, though imperfect, digits). Additionally, a plot illustrating the loss trends for both the Generator and Discriminator over the training period is presented to provide insight into the learning dynamics of the GAN.

QUESTION 4 (Data Poisoning Simulation)
This Programming simulates a data poisoning attack on a sentiment classifier trained on movie reviews. The aim is to show how manipulating training data can harm model performance, especially regarding "UC Berkeley."

We first trained a basic sentiment classifier [mention type] on a small review dataset. The attack involved finding reviews mentioning "UC Berkeley" and flipping their sentiment labels. The classifier was then retrained with this poisoned data.

We compared the model's accuracy and confusion matrices before and after the attack. The results indicate [describe accuracy change]. The confusion matrices show [explain the specific impact on classifying reviews about "UC Berkeley," e.g., more positive mentions misclassified as negative].

This demonstrates how targeted data poisoning can bias a sentiment classifier's predictions for a specific entity. Even minor data manipulation can significantly affect performance and skew sentiment analysis for the targeted term, highlighting a key security concern in machine learning.
