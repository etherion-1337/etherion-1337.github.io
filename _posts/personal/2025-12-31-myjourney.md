---
title: My journey from Quantum to AI
date: 2025-12-31 0000:00:00 +0800
categories: [Personal]
tags: [personal]     # TAG names should always be lowercase
toc: true
---

## Some Background

Towards the end of my PhD in quantum computing, I started exploring the world of quantum machine learning (QML). Back then, QML was still a very young field (honestly, it still is), and everything about it felt incredibly exciting. But I also felt a strong need to deepen my understanding of the fundamentals of machine learning, especially since I was far more fluent in quantum than in classical ML. So after graduation, I spent about 4–5 months learning more. Little did I know that this would end up steering me into an entirely new career.

At the time, data science was being hailed as the “sexiest job” and this was just before COVID. Those few months of study actually helped me secure a spot in AI Singapore’s [AI Apprentice Programme](https://aiap.sg/apprenticeship/), which had a notoriously low acceptance rate. I had intentionally structured my learning plan to cover both the theoretical foundations and the hands-on practical aspects of ML and data science. 

(It wasn’t until much later that I decided to shore up my fundamentals in high-performance computing and GPU programming through [Georgia Institute of Technology’s CS master](https://omscs.gatech.edu/) — but that’s a story for another day.)

Here, I’m listing all the materials I studied during those 4–5 months. Keep in mind that I already had (pretty) advanced math training and experience in C/C++ programming from my undergraduate studies and PhD before making the transition. Still, I expect that anyone with a STEM background will find this list useful to figure out where to start.

## Courses and useful materials

My self-study journey was powered mostly by [Coursera](https://www.coursera.org/) and [DataCamp](https://www.datacamp.com/).

### Introductory C Programming Specialization by Duke University

This [specialization](https://www.coursera.org/specializations/c-programming) consist of 4 courses:
1. Programming Fundamentals
2. Writing, Running, and Fixing Code in C
3. Pointers, Arrays, and Recursion
4. Interacting with the System and Managing Memory

C is the root of most modern programming languages and has had a significant influence on all of them. I first learned C during my undergraduate CS classes and later again during my PhD. I figured a quick refresher course would be a nice way to spend my free time. While C isn’t strictly necessary for ML/NLP (most of it is done in Python), it later became very useful when I started diving into distributed computing, HPC and CUDA.

[Certificate](https://coursera.org/share/d3b709d0eb6141ca6820f1fd207f827f)  
[Notes and Solutions](https://github.com/etherion-1337/Coursera_Intro_to_C_Duke_Uni)

**Verdict**: nice introduction if you have never programmed in your life.

### Python for Everybody Specialization by University of Michigan

This [specialization](https://www.coursera.org/specializations/python) consist of 5 courses:
1. Programming for Everybody (Getting Started with Python)
2. Python Data Structures
3. Using Python to Access Web Data
4. Using Databases with Python
5. Capstone: Retrieving, Processing, and Visualizing Data with Python

This specialization (and the next) from University of Michigan is one of the most popular specialization on Coursera in learning Python. Overall I feel that if you are already comfortable with programming, this one can be skipped. It gives an overview of Python in a functional way.

[Certificate](https://coursera.org/share/d730059ee5939d6353180eeba58f6851)  
[Notes and Solutions](https://github.com/etherion-1337/Python_for_everyone_Uni_Michigan)

**Verdict**: If you are new to programming this is a good one to start, else go for the next one.

### Python 3 Programming Specialization by University of Michigan

This [specialization](https://www.coursera.org/specializations/python-3-programming) consit of 5 courses:
1. Python Basics
2. Python Functions, Files, and Dictionaries
3. Data Collection and Processing with Python
4. Python Classes and Inheritance
5. Python Project: Software Engineering and Image Manipulation

This series of courses will teach you everything you need to know about Python, both in terms of functional development as well as some of the more theoretical aspect of OOP. If you already know programming and want to learn Python, start with this specialization instead of the one above.

[Certificate](https://coursera.org/share/29910f88a686c15d5d8f1a4318b57718)   
[Notes and Solutions](https://github.com/etherion-1337/Python3_Programming_Uni_Michigan)

**Verdict**: Excellent courses on learning Python, one of the best.

### Mathematics for Machine Learning by Imperial College London

This [specialization](https://www.coursera.org/specializations/mathematics-machine-learning) consist of 3 courses:
1. Mathematics for Machine Learning: Linear Algebra
2. Mathematics for Machine Learning: Multivariate Calculus
3. Mathematics for Machine Learning: PCA

This specialization will cover some of the most important maths used in ML. I think in general this serve as a refresher course on maths and also taught me certain mathematica techniques can be utilized in a special way in ML. Overall I think this course is a nice complementary to the programming courses in my self-study journey.

[Certificate](https://coursera.org/share/d4a4c622ac413356a1409f21fb9700d4)     
[Notes](https://github.com/etherion-1337/Coursera_maths_for_ML_ICL/blob/master/Mathematics%20for%20ML%20Coursera%20Notes.pdf)          
[Solution](https://github.com/etherion-1337/Coursera_maths_for_ML_ICL/blob/master/Mathematics%20for%20ML%20Coursera%20work_solution.pdf)        

**Verdict**: If you are not happy with the black box magic behind ML, this specialization is an excellent choices. However, you do need some UG math fundation.

### Machine Learning by Andrew Ng

This [course](https://www.coursera.org/learn/machine-learning) has been revamped and now part of the 3-course specialization. This course by Andrew Ng is perhaps the most famous course in the world and the beginning of many data scientist's journey. Absolutely GOAT and must take.

[Certificate](https://coursera.org/share/a7af8423248ffb1a71f89fff101d8cbe)            
[Notes and Solution](https://github.com/etherion-1337/ML_Andrew_Ng)     

**Verdict**: OG course, a must take.

### Deep Learning Specialization by DeepLearning.AI

This [specialization](https://www.coursera.org/specializations/deep-learning) is again taught by Andrew Ng. This series of courses are slightly more mathematical than his ML courses (his most repeated phrase in the ML class is: "if you do not understand the maths, don't worry about it."). However, I do with he could dive in a bit deeper into the maths portion but I guess he has to strike a balance in this audience. This specialization has 5 courses:
1. Neural Networks and Deep Learning
2. Improving Deep Neural Networks: Hyperparameter Tuning, Regularization and Optimization
3. Structuring Machine Learning Projects
4. Convolutional Neural Networks
5. Sequence Models

Overall I find these courses high-quality and covers till pre-transformer era.

[Certificate](https://coursera.org/share/b29c73b36c5a35eb5b3bad9b02b09f61)              
[Notes and Solution](https://github.com/etherion-1337/Coursera_Deep_Learning_AndrewNg)     

**Verdict**: I personaly feel this is a must-take courses as well, especially you want to cover all basics in deep learning up till transformers.

### Algorithms Specialization by Stanford

I took this [specilization](https://www.coursera.org/specializations/algorithms) purely for interest as I do not have formal CS training back then and algorithm practice (and later, LeetCode) is an activity I always enjoy learning.

1. Divide and Conquer, Sorting and Searching, and Randomized Algorithms
2. Graph Search, Shortest Paths, and Data Structures
3. Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming
4. Shortest Paths Revisited, NP-Complete Problems and What To Do About Them

[Certificate](https://coursera.org/share/2f3e6555730004b935e66c3de6801011)           
[Notes and Solution](https://github.com/etherion-1337/Coursera_Algorithms_Stanford)          

**Verdict**: If you have a CS background, skip this, else take this if you are interested in algorithm. I like the lecturer very much.

### TensorFlow Developer Professional Certificate by DeepLearning.AI

This [specialization](https://www.coursera.org/professional-certificates/tensorflow-in-practice) teach you the fundamental of TensorFlow and prepare you for the certificate. However, given the declining popularty of TF, I would not recommend this. Please spend your time on PyTorch.

1. Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning
2. Convolutional Neural Networks in TensorFlow
3. Natural Language Processing in TensorFlow
4. Sequences, Time Series and Prediction

[Certificate](https://coursera.org/share/3d851aa8bc2988b300db6f4756edfeb0)         
[Notes and Solutions](https://github.com/etherion-1337/Coursera_TF_Dev_Prof_Cert)        

**Verdict**: If you want to learn about TF, go for it. Else I would focus on PyTorch.

### TensorFlow: Advanced Techniques Specialization by DeepLearning.AI

Again this [specialization](https://www.coursera.org/specializations/tensorflow-advanced-techniques) is about TF. Although I like the materials but unfortunately TF is not being used very often now.

1. Custom Models, Layers, and Loss Functions with TensorFlow
2. Custom and Distributed Training with TensorFlow
3. Advanced Computer Vision with TensorFlow
4. Generative Deep Learning with TensorFlow

[Certificate](https://coursera.org/share/497e3fe22556369e3559034d935cb123)            
[Notes and Solutions](https://github.com/etherion-1337/Coursera_TF_Adv_Techniques)        

**Verdict**: Same as above, only take this if you are interested in TF else pass.

### DataCamp

For DataCamp there are many career tracks and each contains a dozen courses covering from basics to advanced topcis. I have completed 4 tracks during my self-study journey:

1. [Python developer](https://app.datacamp.com/learn/career-tracks/python-programmer) (7 courses)      
Cover the basics of Python development      
[Certificate](https://www.datacamp.com/completed/statement-of-accomplishment/track/848010b6734c1d28ff2c0199355f8ea48fbd1349)        
    

2. [Machine Learning Fundamental](https://app.datacamp.com/learn/skill-tracks/machine-learning-fundamentals-with-python) (8 courses)       
Cover most of the library used in data science.      
[Certificate](https://www.datacamp.com/completed/statement-of-accomplishment/track/f9b47797195bce51e8719d7815aa5c2fb485e3cc)

3. [Data Scientist with Python](https://app.datacamp.com/learn/career-tracks/associate-data-scientist-in-python) (37 courses)       
This is a very long series but also a very good one. It teaches you basic stuff like Pandas/SQL all the way to different modelling techniques used in scikit-learn, Keras and PyTorch.         
[Certificate](https://www.datacamp.com/completed/statement-of-accomplishment/track/203f52cec135d0f2880c5846eec14189bd842379)

4. [Data Analyst with Python](https://www.datacamp.com/certification/data-analyst) (15 courses)       
This is largely a subset of the track above, with some addition on SQL.        
[Certificate](https://www.datacamp.com/completed/statement-of-accomplishment/track/2be3aaef90e9ba47bed4d9bed772fd90baf6cf70)

All the 4 tracks have significant amount of overlapping courses so the actual amount of courses taken is much less. Also keep in mind that the course here is much shorter than those in Coursea, I would personally just call them modules instead.

[Combined Notes](https://github.com/etherion-1337/python_basics)  

**Verdict**: I actually learned alot from these modules and I would say it covers comprehensively on the tools I need for the transition.

### AWS Cloud Practitioner and Solutions Architect Associate 

As the last step to conclude my self-study, I actually studied and passed these AWS exam to earn the certificate. I personally feel that they are very useful in my daily work. I used Stephane Maarek's Udemy courses for both [Cloud Practitioner](https://www.udemy.com/course/aws-certified-cloud-practitioner-new/) and [Solution Architect Associate](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/?srsltid=AfmBOoqDYl-ugB36kNOL0Z6EQFIHrkVD9IuvqmKZ4m8BbCoJiNjUAJyo).

These courses are the best of their kind and I have made comprehensive [notes](https://github.com/etherion-1337/AWS_Cert_Prep) on these exams. 

[Cloud Practitioner Certificate](https://www.credly.com/badges/a90a3921-e438-49cd-8ba9-d840641c1e0c/public_url)          
[Solution Architect Associate Certificate](https://www.credly.com/badges/d271f58e-4c49-4fdd-919a-70d9596889ba/public_url)

**Verdict**: Cloud computing is pretty much standard knowledge now and I feel it is a must to know about these technologies.

## Afterthought

As you can see I have crammed a lot of materials in the short span of 4-5 months of full-time self-study and I feel it is totally worth it. I hope this list of study materials is helpful if you come from a STEM background like me. If you are still not satisfied by all these courses, perhaps it is time to consider a proper CS master, like what I did after a few years of working. This is a much tougher route but at the same time much more rewarding. I will cover some of my OMSCS journey later on.