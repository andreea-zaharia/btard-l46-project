# Byzantine Attacks in Distributed Training

This project has been submitted for assessment in the L46 Principles of Machine Learning Systems module, of the Part III Computer Science Tripos at the University of Cambridge.

This project is an investigation into Byzantine attacks and Byzantine fault tolerance in the distributed training of deep learning models. Its objectives are to evaluate the Byzantine-Tolerant All-Reduce (BTARD) algorithm presented by Gorbunov et al. (2021) on a different convolutional model and in the presence of additional types of Byzantine attacks, in a controlled simulation environment.

The implementation builds on the implementation at: https://github.com/yandex-research/btard. 
References:
Gorbunov, E., Borzunov, A., Diskin, M., & Ryabinin, M. (2021). Secure Distributed Training at Scale. arXiv preprint arXiv:2106.11257.
