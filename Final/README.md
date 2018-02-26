# Final Challenge: Build a large-scale image search engine!

## Ranked the 3rd out of 82 submissions.

Due to the limited amount of time and computation resources we have, we can only run a small number of experiments before the deadline. The final model was chosen based on the best accuracy we achieved on the test set. There are still many other models worth exploring and might achieve better accuracy. 

## Abstract

<p style="text-align:justify">
The ubiquitous accessibility and explosive increase of image data has resulted in the property of research in image retrieval. In this paper, we address the task of text-based image retrieval, to select a set of images from a large image database. We vectorized the query descriptions to a sparse binary matrix, employed PLS Regression to learn the common subspace between the visual and textual features, made distance-based relevant image predictions, and rank the relevant images based on a combination of predicted l2-distance and category Jaccard similarity. Experimental results demonstrate that our method effectively utilizes both visual and semantic meanings of the cross-modal information, outperforming other teams on Kaggle competition, and can exploit large scale vision and language datasets for knowledge transfer.
</p>
