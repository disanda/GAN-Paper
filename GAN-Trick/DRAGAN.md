

# ON CONVERGENCE AND STABILITY OF GANS

https://arxiv.org/pdf/1705.07215.pdf


主要对比了原版GAN ，WGAN , WGAN-GP ,以及本文介绍的DRAGAN

总结有如下几点:

1. Use all-convolutional networks which learn their own spatial downsampling (discriminator)or upsampling (generator)
2. Remove fully connected hidden layers for deeper architectures
3. Use batch normalization in both the generator and the discriminator
4. Use ReLU activation in the generator for all layers except the output layer, which uses tanh
5. Use LeakyReLU activation in the discriminator for all layers


## 参考

https://blog.csdn.net/z704630835/article/details/89150051
