---
title: "Bag-of-Words Based Deep Neural Network for Image Retrieval"
collection: publications
permalink: /publication/2014-10-mm-workshop-bing
date: 2014-10-01
venue: "Bing Grand Challenge of the 22th ACM international Conference on Multimedia (ACM MM)"
citation: 'Y Bai, W Yu, <b>T Xiao</b>, C Xu, K Yang, WY Ma, T Zhao. <i>Bing Grand Challenge of the 22th ACM international Conference on Multimedia</i>. <b>ACM MM 2014</b>'
---

[Download paper here](http://ylbai.asiteof.me/grand04_bowdnn_yalongbai.pdf)


## Abstract
This work targets image retrieval task hold by MSR-Bing Grand Challenge. Image retrieval is considered as a challenge task because of the gap between low-level image representation and high-level textual query representation. Recently further developed deep neural network sheds light on narrowing the gap by learning high-level image representation from raw pixels. In this paper, we proposed a bag-ofwords based deep neural network for image retrieval task, which learns high-level image representation and maps images into bag-of-words space. The DNN model is trained on the large scale clickthrough data, and the relevance between query and image is measured by the cosine similarity of query’s bag-of-words representation and image’s bag-ofwords representation predicted by DNN, the visual similarity of images is computed by high-level image representation extracted via the DNN model too. Finally, PageRank algorithm is used to further improve the ranking list by considering visual similarity of images for each query. The experimental results achieved state-of-the-art performance and verified the effectiveness of our proposed method.
