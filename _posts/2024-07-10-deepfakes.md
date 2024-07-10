---
layout: post
title: "Deepfakes: the State of the Field"
---

### TL;DR
This post goes into some detail about the severity of deepfake technology, and the current state of the AI field in trying to reconcile its potential negative impacts.
### Intro
Many global policy actions mention deepfake prevention and mitigation as an important action for successful AI governance. This post aims to distill and communicate the current state of the methods being developed and employed to mitigate and prevent deepfake technology.

Recently, generative deep learning models have improved in capability. Enough to be capable of generating content that is visually indistinguishable from real content by the human eye. Deepfakes are a specific kind of AI-generated content. Media such as images, video, and audio that portrays someone doing something or something happening that never actually happened.

This definition is not very clear, but generally, people use the term 'Deepfake' to refer to AI-generated content created with the goal of deliberately misleading individuals into thinking the content is real - a form of disinformation.

Technologies that manipulate media have existed since before generative AI models were used for this purpose. Adobe Photoshop can be used to create digital content that looks realistic enough to fool a human observer, and has been around for over 30 years. But in terms of the potential for disinformation, Photoshop is much less concerning than Deepfakes, for the following reasons:

1. **Skill Barrier**: only highly-skilled photo editors can create realistic images in Photoshop, acting as a barrier to entry. Producing a deepfake image does require technical ability, but to a far lesser degree than Photoshop (Deepfakes are usually produced just by prompting an image generation model with the details of the expected image).
2. **Time Reduction**: while Photoshopping an image takes a significant amount of time due to the manual efforts required, Deepfakes can be produced nearly instantaneously, making the potential spread of disinformation faster.
3. **Media Formats**: Photoshop is limited to image synthesis, while generative AI models can create convincing video, image, and audio content.
4. **Detection**: there exist methods for detecting Photoshopped images, but there are not yet any tools for Deepfake detection.

There currently exist no technical solutions for the prevention, identification or mitigation of Deepfakes in our information systems. This is a pivotal era for content integrity, knowledge, and trust.
### The Technology Behind Deepfakes
- Deepfakes are typically creating using Generative Adversarial Networks (GANs)
- These models use generator and discriminator sub-models to compete over creating realistic fake images, and identifying fake images among real ones

![Diagram showing a basic GAN](/assets/images/basic-gan.png)

### Approaches to Mitigate and Prevent Deepfakes
%% workflow of a GAN from data collection > model training > generator vs discriminator > output, identifying the interventions in this process, linking back to the backchaining exercise %%
**Prevention Via Data Security**
- Preventing individuals from having access to potential target individuals would mean that they