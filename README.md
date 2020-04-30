# JAX ML Tutorial

## ML from Scratch
A fun and important part of studying machine learning is building models from scratch - that is, without using the prebaked ones available in DL frameworks. What's not fun is calculating derivatives by hand and hard coding them into your models. 

## Automatic Differentiation and JAX
[JAX](https://github.com/google/jax) is a package for [automatic differentiation](https://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/slides/lec10.pdf), which is the fundamental technique that makes it possible for deep learning frameworks like Pytorch and Tensorflow to magically back-propagate all the derivatives through arbitrarily complex models. 

Here we will learn about and create many ML models from scratch while letting JAX take care of automatic differentiation for us. Let's get started!

## Other Useful JAX Tutorials
- JAX Homepage (the first place you should look to learn more about JAX) - https://github.com/google/jax
- You Don't Know JAX (pretty nice beginner overview of JAX in a notebook) - https://github.com/craffel/jax-tutorial/blob/master/you-don-t-know-jax.ipynb
- From Pytorch to JAX (introduces a lot of cool ideas about how to work with JAX, compared to Pytorch; in particular, includes details about "purifying" functions to work with classes) - https://sjmielke.com/jax-purify.htm

There is also some interesting discussion of JAX on [Reddit r/MachineLearning](https://www.reddit.com/r/MachineLearning/)
