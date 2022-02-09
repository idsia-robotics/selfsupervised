---
layout: splash
title: Research on Self-Supervised Learning for Perception
header:
  image: /files/img/header.jpg
---

<html>

<head>
    <script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    </script>

  <script type="text/javascript" src="https://npmcdn.com/flickity@2/dist/flickity.pkgd.js">
  </script>

  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width initial-scale=1" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge">

  <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="//cdn.rawgit.com/jpswalsh/academicons/master/css/academicons.min.css">
  <link rel="stylesheet" href="{{'/css/flickity.css'| relative_url }}">
  <link rel="stylesheet" href="{{'/css/csl-blocks.css'| relative_url }}">
  <!-- <link rel="stylesheet" href="{{'/css/bootstrap.min.css'| relative_url }}"> -->
  <!-- <link rel="stylesheet" href="{{'/css/main.css'| relative_url }}"> -->

</head>

<body>

<div markdown="1">
# Introduction
</div>

<p>
Advances in deep neural network architectures and the availability of large-scale labeled datasets fueled a new wave of ai systems, enabling technologies that only 10 years ago seemed science-fiction. While results are astonishing, they overshadow a fundamental problem of this kind of system: learning very little information from a large dataset of labeled examples, which are often produced by human experts, and require a lot of resources in the making. Humans, instead, require much less information to learn new tasks &mdash; even the complex ones such as driving &mdash; something attributed to our vast background knowledge on how the world works, to our intuition about simple physics and geometry. As early as babies in our stroller, we start observing the world evolving around us, taking actions and seeing the consequences, internally building a predictive model of the world by testing our hypothesis about the future against reality. <a href="https://ai.facebook.com/blog/self-supervised-learning-the-dark-matter-of-intelligence/">Self-supervised learning</a> is a new machine learning paradigm that tries to imitate this mechanism, learning as much as possible from observations of the world, which by themselves enable the training of predictive models without the use of explicit labels. Once trained, these models can quickly learn our specific task of interest and do so with much less labeled data.
<br/>
Our research on self-supervised learning at IDSIA mainly focuses on visual perception applied to real robotic tasks, such as identifying obstacles, localizing objects of interest, other robots, and people around us. This page summarizes the research findings, including videos of proposed approaches applied to multiple robot platforms in different environments.
</p>


<!-- separator -->


<div markdown="1">
# Publications
</div>
<div markdown="1">
## Learning Visual Localization of a Quadrotor using its Noise as Self-Supervision
</div>
Mirko Nava, Antonio Paolillo, Jérôme Guzzi, Luca M. Gambardella, and Alessandro Giusti<br/>
_in IEEE Robotics and Automation Letters, vol. 7, pp. 2218-2225, 2022._

<div>
<div class="csl-pdf"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9686072">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #nava2022learning-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #nava2022learning-bibtex, #nava2022learning-show {
      display: none;
  }
</style>

<input type="checkbox" id="nava2022learning-show" />
<div class="csl-bibtex"> <label class="csl-label" for="nava2022learning-show"><span class="csl-label">BIBTEX</span></label></div>
<div class="csl-doi"><a href="https://doi.org/10.1109/LRA.2022.3143565">DOI</a></div>

<div id="nava2022learning-bibtex">
  <pre>@article{nava2022learning,
  author={M. {Nava} and A. {Paolillo} and J. {Guzzi} and L. M. {Gambardella} and A. {Giusti}},
  journal={IEEE Robotics and Automation Letters}, 
  title={Learning Visual Localization of a Quadrotor Using its Noise as Self-Supervision}, 
  year={2022},
  volume={7},
  number={2},
  pages={2218-2225},
  doi={10.1109/LRA.2022.3143565}
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We introduce an approach to train neural network models for visual object localization using a small training set, labeled with ground truth object positions, and a large unlabeled one. We assume that the object to be localized emits sound, which is perceived by a microphone rigidly affixed to the camera. This information is used as the target of a cross-modal pretext task: predicting sound features from camera frames. By solving the pretext task, the model draws self-supervision from visual and auditory data. The approach is well suited to robot learning: we instantiate it to localize a small quadrotor from 128x80 pixel images acquired by a ground robot. Experiments on a separate testing set show that introducing the auxiliary pretext task yields large performance improvements: the Mean Absolute Error (MAE) of the estimated image coordinates of the target is reduced from 7 to 4 pixels; the MAE of the estimated distance is reduced from 28 cm to 14 cm. A model that has access to labels for the entire training set yields a MAE of 2 pixels and 11 cm, respectively.
  </p>
</details>

<div class="video-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/x7Xt7Xr7pWk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen />
</div>

</div>


</body>

</html>
