# isomap-learning-tool

This is a potential project for the Artificial Intelligence course (EN.601.464) at JHU. This was made by Joshua Brown in Spring 2025 as part of the final project (Project 7) for the class.

Students will start by reading the explanation of what the Isomap algorithm is. While the explanations provided (written by me, a student, so there may be some slight flaws, but they should be relatively accurate) should be sufficient, students can learn more by clicking on some of the attached links if they are interested, or if it helps them. Then, they are asked to implement Isomap manually: this involves 4 primary functions representing different tasks done in the algorithm. A 5th function to put their functions together is also defined for them. 

After this, students run their code and evaluate their Isomaps ability to classify digits from a dataset of handwritten digit images (this is a supervised usage). They start with classifying into two numbers (that should be easy to distinguish, chosen by them so that they can explain their reasoning). They run this on an Isomap that considers 8 nearest neighbors for each sample point and 2 components from the eigendecomposition step, and then again with 5 components from the eigendecomposition step. They evaluate the difference in performance between these two and are asked to try their best to explain why the difference in performance happened (implying that they should consider the effects of considering different amounts of components). 

Then, they run the Isomap (without judging performance) in an unsupervised manner to classify all 10 digits (0-9), and compare how the data is separated into clusters with how PCA (principal component analysis) performs the same separation. They form two 3D graphs, one from PCA, the other from Isomap, to evaluate the ability to form clusters qualitatively. They can also (if they choose) use code provided to make a GIF rotating around the 3D graph to better display the clusters. They are then asked to analyze the following questions: 
* Did PCA or Isomap classification do a better job separating between the digits? Evaluate this qualitatively based on the 3D scatter plots. 
* Also, if one of the models had better distinctions between digits, explain why you think that occurred.
* Was there any particular number that Isomap did a good or bad job distinguishing between? What do you think some benefits of using ISOMAP, a dimensionality reduction method preserving distances, are compared to using something like principal component analysis (PCA), which focuses on preserving variance? 

Between writing the code and answering the questions, both designed to inspire intuition, students should have developed a decent understanding of what the Isomap algorithm/tool is, even without going too deep into the mathematical components, making it a perfect project for an artificial intelligence course.

With most of the explanations for what students observe or predict, an honest attempt should suffice for full credit, as some of the intuition can be advanced and would not be completely reasonable to expect students to master.
