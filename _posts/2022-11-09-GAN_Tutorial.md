---
layout: post
title:  "GAN Tutorial"
date:   2022-11-12
author: KIM JeongHyeon and Khan Osama
categories: Generative Adversarial Networks
tags: GAN Tutorial
use_math: true
---

# Content
This report summarizes the tutorial presented by Ian Goodfellow at NIPS in 2016. The author answers five questions regarding generative adversarial networks (GAN) in the tutorial. These questions are:
- Why is generative modeling a topic worth studying?
- How do generative models work? Comparison of other generative models with GAN
- How do GANs work?
- What are some of the research frontiers in GANs?
- What are some state-of-the-art image models that combine GANs with other methods?
In this post, we will go through every single question and try to answer them as clearly as possible. To better grasp GANs, we modified the order of these questions.


# Internals Of GANs

Generative models refer to any model that takes a training set consisting of samples drawn from a distribution p<sub>data</sub> and learns to represent an estimate of that distribution. Here p<sub>data</sub> describes the actual distribution that our training data came from. A generative model aims to learn a distribution p<sub>model</sub>, such that this distribution is close to the actual data distribution as much as possible. Generative models are classified into two main categories; Those where we represent the p<sub>model</sub> with an explicit probability distribution and those where we do not have an explicit distribution but can sample from it. GAN belongs to the second one. 

## The GAN framework

## Training Process

## Optimal Discriminator 

## Non-Saturating Game

## GANs and Maximum Likelihood Game

## Divergence and GANs

## Tips and Tricks

# Applications Of GANs

# Research Frontiers

## Non-convergence

## Mode Collapse

## Evaluation of GANs

## Discrete Outputs

## Others


