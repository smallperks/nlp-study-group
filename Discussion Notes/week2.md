# Week 2 - SVD & NMF

SVD Notes:
* SVD - whether to center the data or not is domain specific. For example, in physics, due to phsyical limitations, it might not make sense to center the data. 
* SVD - You don't need to standardize the input because the singular value matrix, sigma, will incorporate that in its values. I.e. if you don't normalize the input, the diagnoal values in sigma will be larger. 
* Multiple SVD implementations:
  * Randomized SVD - random initialization of the factored matrices. There's a facebook implementation as well: https://research.fb.com/blog/2014/09/fast-randomized-svd/
  * Truncated SVD - instead of computing the full matrix factors, it computes truncated versions depending on how many dimensions you're interested in. For example, in the nlp case, if you're only interested in the top 10 topics, you would pass k=10 to the truncated svd algo.
  * Full SVD
* There's a section on using SVD to extract foreground and background from images. 
  * It actually uses a video where each frame is an unrolled array. SVD then finds the axes of highest variance which can then be used to extract out foreground and background

SVD applications:
* Whenever you have a large data matrix and you want to find the main components, the dimensions along which the data varies greatly
* Can also be used to fill in missing values
* Face decomposition
* Audio Source decomposition
* Topic Modelling

Why do we want things in low-dimensions?:
* Visualization
* Filtering out noise (re: PCA paper with the physics spring model)
* As a pre-processing step so that we can use more computationally expensive tools on the data

SVD Cons:
* Non trivial to understand the latent space always - for example in images, it's hard to understand what each resulting latent-dimension means
* In the case of NLP, SVD itself doesn’t give you the labels for each of the latent axes, you need to take an additional step to say that the top X words describe this axi (topic)
  
