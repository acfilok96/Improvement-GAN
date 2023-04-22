# Improvement-On-Generative-Adversarial-Network

Generative Adversarial Networks, or GANs for short, are an approach to generative modeling using deep learning methods, such as convolutional neural networks.

Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the regularities or patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.

GANs are a clever way of training a generative model by framing the problem as a supervised learning problem with two sub-models: the generator model that we train to generate new examples, and the discriminator model that tries to classify examples as either real (from the domain) or fake (generated). The two models are trained together in a zero-sum game, adversarial, until the discriminator model is fooled about half the time, meaning the generator model is generating plausible examples.

GANs are an exciting and rapidly changing field, delivering on the promise of generative models in their ability to generate realistic examples across a range of problem domains, most notably in image-to-image translation tasks such as translating photos of summer to winter or day to night, and in generating photorealistic photos of objects, scenes, and people that even humans cannot tell are fake.

Generative Adversarial Networks (GANs) are a novel class of deep generative models with significant attention nowadays. GANs learn complex and high-dimensional distribution implicitly over images, audio, and data. However, there exist significant challenges in the training of GNAs like mode collapse, non-convergence, and instability, due to inappropriate design of network architecture, use of objective function, and selection of optimization algorithm. Recently, to address these challenges, several solutions for better optimization of GANs have been investigated based on techniques of re-engineered network architectures, now objective function, and alternative optimization algorithms. To the best of my knowledge, there is no existing survey that has particularly focused on the board and systematic developments of these solutions.

In this project, the several problems on GAN are tried to resolve using a novel approach.

Results are given below for various datasets.


Generated Anime Image:-

![Alt Generated Anime Image](https://github.com/acfilok96/Improvement-On-Generative-Adversarial-Network/blob/main/Files/Animo%20Data/Generated%20Images.png)


Generated Celeb Face Image:-

![Alt Generated Celeb Face Image](https://github.com/acfilok96/Improvement-On-Generative-Adversarial-Network/blob/main/Files/Celeb%20Data/Generated%20Celeb%20Images.png)


Generated Flower Image:-

![Alt Generated Flower Image](https://github.com/acfilok96/Improvement-On-Generative-Adversarial-Network/blob/main/Files/Flower%20Data/Generated%20Images.png)


Generated Abstract Image:-

![Alt Generated Abstract Image](https://github.com/acfilok96/Improvement-On-Generative-Adversarial-Network/blob/main/Files/Abstract%20Image%20Data/Generated%20Abstract%20Images.png)
