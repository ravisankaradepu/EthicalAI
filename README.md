# Awesome Ethical AI
A list of awesome papers and cool resources on Ethical AI in general! 
This is a work in progress list, we keep adding list of papers in general and other subfields of Ethical AI.

# Table of Contents

* [Tutorial and Blogs](#tutorials-and-blogs)
* [Papers](#papers)
  * [Surveys](#surveys)
   

# Tutorials and Blogs 

* [Transfer Learning − Machine Learning's Next Frontier](http://ruder.io/transfer-learning/index.html)
* [A Little Review of Domain Adaptation in 2017](https://artix41.github.io/blog/2018-01-03-domain-adaptation-2017/)
* [A Comprehensive Hands-on Guide to Transfer Learning with Real-World Applications in Deep Learning](https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a)

# Papers

Papers are ordered by theme and inside each theme by publication date (submission date for arXiv papers). If the network or algorithm is given a name in a paper, this one is written in bold before the paper's name.

## Surveys

* [A Survey on Transfer Learning](https://www.cse.ust.hk/~qyang/Docs/2009/tkde_transfer_learning.pdf) (2009)
* [Transfer Learning for Reinforcement Learning Domains: A Survey](http://www.jmlr.org/papers/volume10/taylor09a/taylor09a.pdf) (2009)
* [A Survey of transfer learning](https://link.springer.com/article/10.1186/s40537-016-0043-6) (2016)
* [Domain Adaptation for Visual Applications: A Comprehensive Survey](https://arxiv.org/abs/1702.05374) (2017)
* [Deep Visual Domain Adaptation: A Survey](https://arxiv.org/abs/1802.03601) (2018)

transfer between real and synthetic signs.
* [NYU Depth Dataset V2](http://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html): labeled paired images taken with two different cameras (normal and depth)
* [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html): faces of celebrities, offering the possibility to perform gender or hair color translation for instance
* [Office-Caltech dataset](https://people.eecs.berkeley.edu/~jhoffman//domainadapt/): images of office objects from 10 common categories shared by the Office-31 and Caltech-256 datasets. There are in total four domains: Amazon, Webcam, DSLR and Caltech.
* [Cityscapes dataset](https://www.cityscapes-dataset.com/): street scene photos (source) and their annoted version (target)
* [UnityEyes](http://www.cl.cam.ac.uk/research/rainbow/projects/unityeyes/) vs [MPIIGaze](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/gaze-based-human-computer-interaction/appearance-based-gaze-estimation-in-the-wild-mpiigaze/): simulated vs real gaze images (eyes)
* [CycleGAN datasets](https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/): horse2zebra, apple2orange, cezanne2photo, monet2photo, ukiyoe2photo, vangogh2photo, summer2winter
* [pix2pix dataset](https://people.eecs.berkeley.edu/~tinghuiz/projects/pix2pix/datasets/): edges2handbags, edges2shoes, facade, maps
* [RaFD](http://www.socsci.ru.nl:8180/RaFD2/RaFD?p=main): facial images with 8 different emotions (anger, disgust, fear, happiness, sadness, surprise, contempt, and neutral). You can transfer a face from one emotion to another.
* [VisDA 2017 classification dataset](http://ai.bu.edu/visda-2017/#browse): 12 categories of object images in 2 domains: 3D-models and real images.
* [Office-Home dataset](http://hemanthdv.org/OfficeHome-Dataset/): images of objects in 4 domains: art, clipart, product and real-world.
* [DukeMTMC-reid](https://github.com/layumi/DukeMTMC-reID_evaluation) and [Market-1501](http://www.liangzheng.org/Project/project_reid.html): two pedestrian datasets collected at different places. The evaluation metric is based on open-set image retrieval. 

## Text-to-text

* [Amazon review benchmark dataset](https://www.cs.jhu.edu/~mdredze/datasets/sentiment/): sentiment analysis for four kinds (domains) of reviews: books, DVDs, electronics, kitchen
* [ECML/PKDD Spam Filtering](http://www.ecmlpkdd2006.org/challenge.html#download): emails from 3 different inboxes, that can represent the 3 domains.
* [20 Newsgroup](http://qwone.com/~jason/20Newsgroups/): collection of newsgroup documents across 6 top categories and 20 subcategories. Subcategories can play the role of the domains, as describe in [this article](https://arxiv.org/pdf/1707.01217.pdf).

# Results

The results are indicated as the prediction accuracy (in %) in the target domain after adapting the source to the target. For the moment, they only correspond to the results given in the original papers, so the methodology may vary between each paper and these results must be taken with a grain of salt.

## Digits transfer (unsupervised)
# Challenges

* [Visual Domain Adaptation Challenge (VisDA)](http://ai.bu.edu/visda-2017/)
* [Open AI Retro Contest](https://blog.openai.com/retro-contest/)

# Libraries

* Domain Adaptation: [Salad](https://github.com/domainadaptation/salad) (Semi-supervised Adaptive Learning Across Domains)

# Books

* [Transfer Learning for Natural Language Processing](https://www.manning.com/books/transfer-learning-for-natural-language-processing)
* [Hands-On Transfer Learning with Python](https://learning.oreilly.com/library/view/hands-on-transfer-learning/9781788831307) | [GitHub Repo](https://github.com/dipanjanS/hands-on-transfer-learning-with-python)
