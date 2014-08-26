---
title: Ask Peter Norvig
layout: post
author: brian

published: true
---

When we first began Leada, we tried to better understand the data science industry by interviewing professionals in the field. As students simply wanting to learn more about data science, we ultimately created a free resource to inform both undergraduates and professionals about the data science industry. We accomplished this by having Q & A interviews with experts such as Mike Olsen, Hal Varian, and Tom Davenport and Data Scientists at LinkedIn, Facebook, Yelp, and more.

The Data Analytics Handbook was not only instrumental in giving us the understanding we needed to feel confident in what we were creating; but was downloaded over 25,000 times, gave us dozens of warm contacts, and an immediate group of early adopters. Some experts took longer to contact than others (I emailed Hal Varian over 8 times!) but you’d be surprised who you can get 25 minutes of time to help inform others. [Download the Handbook Here](http://www.teamleada.com/handbook)

<p align="center">
  <img src ="/assets/images/post_assets/Ask_Peter/books_image.jpg"> </img>
</p>

As a conclusion to The Data Analytics Handbook, we thought it would be fun to see what questions our readers had about data science, and then had them answered by the #3 ranked most powerful data scientist in the world today by Forbes and Director of Research at Google, Peter Norvig.

A month ago, we allowed readers to submit questions about the data science industry and we took the top 8 most popular questions. Below are Peter’s responses, thanks to everyone who participated, [Elizabeth Lin](http://www.elizabethylin.com/about/) for designing the handbook, and a big thanks to Peter!

<strong>Q1: What is your opinion on using online education (Coursera, Udacity, etc.) vs. formal education (Masters in Analytics) for industry professionals looking to develop data science skill? (174 Up-votes)</strong>

I think more important than either "formal education" or online education would be real-world experience.  Yes, you do need to get some theory, but it is more important to get lots of practice. So take a University class if that is convenient, or an online class if that makes more sense for you, but then get to work on some real data and figure out how to apply what you learned to a data set, then keep at that.

<strong>Q2: What is one of the most-often overlooked things in machine learning that you wished more people would know about or would study more? What are some of the most interesting data science projects Google is working on? (52 Up-votes)</strong>

It is sometimes overlooked that different machine learning problems are in totally different regimes. Obviously there are differences in the size of problems: the number of rows (examples) and columns (features) can vary from dozens to billions, but there are other differences that are less obvious: stationarity (are the examples changing over time), transfer (can we train on one data set and apply what we learned to a different set), sparsity (how many of the possible examples are represented in the data), structure (can the problem be represented as a vector of real numbers, or is some other representation necessary), and so on.

Google has a lot of interesting projects. In terms of problem areas, obviously there are many projects to better match search results, and separately, ads results, to your query.  But there is also work in speech recognition, machine translation, image and video understanding, handwriting and gesture recognition, recommendations of music, apps, friends on G-Plus, etc.  All these involve machine learning. And behind the scenes we apply machine learning to optimize our own operations: how we allocate jobs to different computers, flow data through our networks, etc.

In terms of tools, Google is building a variety of tools to handle different types of machine learning problems.  One big issue is scale: how can we handle ever-bigger data sets.  Another is moving from batch models (here is a fixed data set) to stream models (the data set is continually updated, second by second).

<strong>Q3: What books have influenced your thinking the most and/or what books do you think you've learned the most from? (43 Up-votes)</strong>

Structure and Interpretation of Computer Programs really solidified and gave names to the concepts I had been learning about programming.  Kevin Murphy's new "Machine Learning" book is, for me, the best of the current ML books.  I also learned a lot from the lecture notes by Andrew Ng and Andrew Moore. Judea Pearl's book Probabilistic Reasoning in Intelligent Systems, and before the book his papers and hearing him talk in person, demonstrated to me why I was having so much trouble trying to build systems based on Boolean logic, and showed that probability is the right foundation for dealing with any situation that involves uncertainty.  Also: The Inmates are Running the Asylum, Programming Pearls, and The Practice of Programming.

<strong>Q4: How important is data science for individuals interested in applied machine learning and deep learning? (42 Up-votes)</strong>

I'm not really sure what "data science" means.  It seems to be a term first promoted by journalists, and now we're all left trying to figure it out what.  Wikipedia says it is statistics plus programming skill plus expertise in a particular subject matter.  If that's so, then it is hard to tell the difference between "applied machine learning" and "data science".

<strong>Q5: What, say, 3 recent papers in machine learning do you think will be influential to directing the cutting edge of research these days? (41 Up-votes)</strong>

I've never been able to pick lasting papers in the past, so don't trust me now, but here are a few:

Rendle's "Factorization Machines"
Wang et al. "Bayesian optimization in high dimensions via random embeddings"
Dean et al. "Fast, Accurate Detection of 100,000 Object Classes on a Single Machine"

<strong>Q6: Do you think Deep learning/Neural Networks is the future? (36 Up-votes)</strong>

I never thought that "neural networks" was a useful category.  We want to train some function to set parameters to minimize an expected loss function, and whether the function you are training is called a "neural network" or not just seems like an unimportant detail.  The fact that they are "semi-parametric" -- they have a very large number of parameters, but do not rely on keeping all data points around -- is certainly important, and I think the semi-parametric space is a very important one.  As for deep learning, it is certainly also extremely important to be able to create representations at multiple levels, even when the intermediate levels are not accessible in the data.  The current work called "deep learning" has an approach for dealing with this issue, but it is not the only possible approach.

<strong>Q7: Which organization/university/group according to you is at the forefront of artificial intelligence? (35 Up-votes)</strong>

I don't think any group has a monopoly on good work.  No matter where you are, you have an opportunity to advance the field.

<strong>Q8: How important is naive physics and common sense reasoning?</strong>

I think this gets back to the deep learning question.  In non-naive physics, we have a great theory of the world that can be used with precise measurements of quantities.  In naive physics, we apply lessons learned from that theory to the case where we don't have precise measurements.  So naive physics tells us that water flows downhill, but doesn't tell us how fast.  So think of this as a level of representation that is above the particle-by-particle laws of physics.  I think if we make progress at having different types of representations, we won't need specialized theories of naive physics.

