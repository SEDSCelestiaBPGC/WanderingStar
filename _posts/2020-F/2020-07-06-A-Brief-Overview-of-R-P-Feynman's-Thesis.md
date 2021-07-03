---
layout: post
author: Bhuvan S V
tags: ["Astrophysics", "Author:Bhuvan S V", "Physics", "RP Feyman", "Science", "SEDS Celestia"]
category: "Science"
type: Blog
image: "assets/posts/2020/RPF2020.jpeg"
---

![RPF2020](../assets/posts/2020/RPF2020.jpeg)

## Introduction

Richard Feynman is one of the most famous physicists of the 20th century, changing our notion of a typical scientist (the uncombed, white hair, a big mustache, donning a white coat, can be attributed largely to Einstein). While we know him as the prank-loving, bongo-playing, safe-cracking, and feminizing genius, most of us forget about his contributions to  physics, especially the field of Quantum Chromodynamics (or QCD), for which he won the 1965 Nobel Prize in Physics, along with Julian Schwinger and Schin’ichiro Tomonaga.Two of his works are well known. The first, now known as Feynman diagrams, simplified large equations to easily understandable diagrams, which has made the works of many particle physicists easier. The second, the path integral formulation, was, and still is, a very important tool in quantum mechanics. In this article, we shall see the origins of the path integrals, in his 1942 PhD Thesis.
\
![R P Feynman](https://i.imgur.com/0TmWgr5m.png)

## Motivation

Consider a free charged particle accelerating in space. As any accelerated charge would, this particle would emit radiation, thereby losing energy (law of conservation of energy). This loss of energy is simply explained in case of a charged particle in a potential field; say an electron in an atom- the potential of the positively charged nucleus would do the work necessary to decrease the energy of the electron. But for a free charge, there is no such potential to do the needed work.

![Imgur](https://i.imgur.com/1gNnE1cm.png)  

The then accepted explanation was that the charged particle would act on itself- the work is done due to “self-energy”. Feynman wished to remove this self-energy, by introducing another charge particle, which would act on the radiating particle. This can be possible when one sees that Maxwell’s equations allow for two solutions- one with positive time and other with negative time. The mechanism is as follows: the radiation from particle 1 would cause particle 2 to emit radiation back to particle 1, thereby affecting it. This seemingly violates principle of causality, but when you consider a large number of particles and both solutions of Maxwell’s equations, this is seen to actually obey it. Feynman calls this theory, which he developed along with his advisor John Archibald Wheeler, the theory of action at a distance (now called Wheeler-Feynman absorber theory). The main principles of this theory are as follows:  

1. Acceleration of a charged particle is due to its sum interactions with other charged particles, or, there is no “self-energy”. This also means that a free particle alone cannot spontaneously emit radiation.

2. The force due to the charged particles is the Lorentz force, or, there is no underlying field in free space.

3. The fundamental phenomena in nature are symmetrical with respect to past and future. This means, the solutions to Maxwell’s equations are sum of half the retarded (positive time) solution and half the advanced (negative time) solution.

Since this theory is difficult to represent in Hamiltonian formulation (it isn’t possible to express as harmonic oscillators, as there are other interactions as well), we use the principle of least action from classical mechanics to find the equations of motion. We also note that the Wheeler-Feynman theory is now considered to be not true.

### I. Least action in classical mechanics:

The first part of the thesis deals with the principle of least action in classical mechanics. To go further we need to be familiar with some terms and results that shall be used throughout the thesis:

1. **Functional**: A functional analogy 

