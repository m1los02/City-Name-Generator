# City-Name-Generator

This project is inspired by Andrej Karpathy’s makemore series, which teaches how to build neural networks from scratch in a really hands-on way. I’m doing this as part of my learning process to better understand how neural networks and natural language processing (NLP) work.   

The main idea is to train a neural network that can generate new city names that sound like real U.S. cities. It won’t be copying existing names, but instead learning patterns from them, like common letter combinations and name structures, to come up with completely new (and hopefully realistic-sounding) ones.   

For the data, I’m using a U.S. cities dataset from SimpleMaps.com. It includes a bunch of information like the city name, state, and county, but for this project I’m only using the city names. That’s all the model needs to learn how cities are usually named in the U.S.   

This project is mostly for practice and experimenting.  

This project also includes ideas and techniques from a few well-known research papers:  
- Bengio et al. (2003) – for using embeddings to represent characters in a more meaningful way.  
- Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift – for adding a BatchNorm layer to help stabilize variance and speed up training.
- Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification – for using Kaiming (He) initialization to improve weight initialization.
- WaveNet: A Generative Model for Raw Audio – for the WaveNet architecture.
