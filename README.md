# XMV
Pytorch implementation for Self-supervised Modal and View Invariant Feature Learning

# Abstract

Most of the existing self-supervised feature learning methods for 3D data either learn 3D features from point cloud data or from multi-view images. By exploring the inherent multi-modality attributes of 3D objects, in this paper, we propose to jointly learn modal-invariant and view-invariant features from different modalities including image, point cloud, and mesh with heterogeneous networks for 3D data. In order to learn modal- and view-invariant features, we propose two types of constraints: cross-modal invariance constraint and cross-view invariant constraint. Cross-modal invariance constraint forces the network to maximum the agreement of features from different modalities for same objects, while the cross-view invariance constraint forces the network to maximum agreement of features from different views of images for same objects. The quality of learned features has been tested on different downstream tasks with three modalities of data including point cloud, multi-view images, and mesh. Furthermore, the invariance cross different modalities and views are evaluated with the cross-modal retrieval task. Extensive evaluation results demonstrate that the learned features are robust and have strong generalizability across different tasks.


# Framework

![](./figure/framework.pdf)

The proposed framework learns modality and view invariant features which makes the cross-modal retrieval for 3D objects possible.



# Cross-modal retrieval results


![](./figure/retrieval-results.pdf)
