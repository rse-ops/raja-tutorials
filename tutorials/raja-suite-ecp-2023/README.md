# RAJA Portability Suite Tutorial

> For ECP 2023

Welcome to the RAJA Portability Suite tutorial. In this tutorial you will learn
how to write an simple application that can target different hardware
architectures using the RAJA and Umpire libraries.

## Lessons

You can find lessons in the lessons subdirectory. Each lesson has a README file
which will introduce new concepts and provide instructions to move forward. 

Each lesson builds upon the previous one, so if you get stuck, you can look at
the next lesson to see the complete code. You can go through these lessons
as files here, or use the Docker container / playground tutorial provided,
with instructions below:

## Usage

To build the container to test locally:

```bash
$ docker build -t raja-suite-2023 .
```

And run the container locally (using default password):

```bash
$ docker run -it -p 3000:3000 raja-suite-2023
```

And open your host to [127.0.0.0:3000](http://127.0.0.0:3000). You can open the tutorial by
opening the folder at `/home/rajadev` and starting at the README.md.
