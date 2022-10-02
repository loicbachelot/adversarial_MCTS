# adversarial_MCTS

Adversarial learning model applied to puzzle solving

In this repo you will find a sample of the code, the related paper I wrote and the presentation.

This project was my research project for my last year of Master. It is part of a bigger project including a MCTS method to solve puzzle. 

The goal of this research is to propose a method to automatically re-assemble archaeological artifacts from fragments to help archaeologists in their work. We suggest that, fragments reassembly can be simplified to a puzzlereconstruction problem, which may be solved by computer vision algorithms. In this paper we discuss the reassembly from 9 fragments. Given an unordered set of fragments, we try to merge them back to the original image. The main contributions of this work is the comparison between the four following methods: two discriminator-based reassembly methods using deep learning to predict the probability of the positions for each available fragments; a Monte Carlo Tree Search (MCTS) based method inspired by AlphaZero to reconstruct the image; and a combined method based on the MCTS using a discriminator as the value prediction. The results show the benefits of using both a discriminator and an MCTS algorithm.

Work supervised by Marie-Morgane Paumard and David Picard, in collaboration with Johan Gras
