---
layout: splash
title: Self-Supervised Learning for Perception
header:
  image: /files/img/header.jpg
---

<html>
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width initial-scale=1" >

  <script type="text/javascript" src="https://npmcdn.com/flickity@2/dist/flickity.pkgd.js"></script>
  <script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
  <script>
    function show_bibtex(e){
      document.querySelector('pre.bibtex[data-ref="' + e.dataset.ref + '"]').classList.toggle("show");
    }
  </script>

  <style type="text/css">
    pre.bibtex {
        transition: height 0.2s ease-in-out,
            width 0.3s ease-in-out,
            opacity 0.1s ease-in-out,
            padding 0.1s ease-in-out,
            margin 0.1s ease-in-out;
    }

    pre.bibtex:not(.show) {
        width: 0;
        height: 0;
        opacity: 0;
        padding: 0;
        margin: 0;
    }
  </style>
  <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="//cdn.rawgit.com/jpswalsh/academicons/master/css/academicons.min.css">
  <link rel="stylesheet" href="{{'/css/flickity.css'| relative_url }}">
  <link rel="stylesheet" href="{{'/css/csl-blocks.css'| relative_url }}">
  <!-- <link rel="stylesheet" href="{{'/css/bootstrap.min.css'| relative_url }}"> -->
  <!-- <link rel="stylesheet" href="{{'/css/main.css'| relative_url }}"> -->
</head>
<body>


<h1>About</h1><a id="about"></a>


<p>
Todo
</p>


<h1>Publications</h1><a id="publications"></a>


<div>
  <h2>Self-Supervised Prediction of the Intention to Interact With a Service Robot</h2>
  <p>
      Gabriele Abbate, Alessandro Giusti, Viktor Schmuck, Oya Celiktutan, and Antonio Paolillo<br />
      <i>in Robotics and Autonomous Systems, 2023.</i>
  </p>

  <a href="https://arxiv.org/pdf/2309.07477">
      <div class="tag pdf">Preprint PDF</div>
  </a>
  <!-- <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9686072">
      <div class="tag pdf">PDF</div>
  </a> -->
  <!-- <a>
      <div class="tag bibtex" onclick="show_bibtex(this)" data-ref="abbate2023self">BIBTEX</div>
  </a> -->
  <!-- <a href="https://doi.org/10.1109/LRA.2022.3143565">
      <div class="tag doi">DOI</div>
  </a> -->

  <pre class="bibtex no-scrollbar" data-ref="abbate2023self">Bibtex entry here.</pre>

  <details>
      <summary>Abstract</summary>
      <p>
          A service robot can provide a smoother interaction experience if it has the
          ability to proactively detect whether a nearby user intends to interact, in
          order to adapt its behavior e.g. by explicitly showing that it is available to
          provide a service. In this work, we propose a learning-based approach to
          predict the probability that a human user will interact with a robot before
          the interaction actually begins; the approach is self-supervised because after
          each encounter with a human, the robot can automatically label it depending on
          whether it resulted in an interaction or not. We explore different
          classification approaches, using different sets of features considering the pose
          and the motion of the user. We validate and deploy the approach in three
          scenarios. The first collects 3442 natural sequences (both interacting and
          non-interacting) representing employees in an office break area: a real-world,
          challenging setting, where we consider a coffee machine in place of a service
          robot. The other two scenarios represent researchers interacting with service
          robots (200 and 72 sequences, respectively). Results show that, even
          in challenging real-world settings, our approach can learn without external
          supervision, and can achieve accurate classification (i.e. AUROC greater
          than 0.9) of the user's intention to interact with an advance of more than 3 s
          before the interaction actually occurs.
      </p>
  </details>

  <!-- video here <iframe src="https://www.youtube.com/embed/fuexj03mGNo" frameborder="0" allow="autoplay; encrypted-media" 
      style="aspect-ratio: 16/9; width: 80%;" allowfullscreen></iframe> -->
</div>


<div>
  <h2>Learning Visual Localization of a Quadrotor using its Noise as Self-Supervision</h2>
  <p>
  Mirko Nava, Antonio Paolillo, Jérôme Guzzi, Luca Maria Gambardella, and Alessandro Giusti<br/>
  <i>in IEEE Robotics and Automation Letters, vol. 7, pp. 2218-2225, 2022.</i>
  </p>

  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9686072"><div class="tag pdf">PDF</div></a>
  <a><div class="tag bibtex" onclick="show_bibtex(this)" data-ref="nava2022learning">BIBTEX</div></a>
  <a href="https://doi.org/10.1109/LRA.2022.3143565"><div class="tag doi">DOI</div></a>

  <pre class="bibtex no-scrollbar" data-ref="nava2022learning">@article{nava2022learning,
  author={M. {Nava} and A. {Paolillo} and J. {Guzzi} and L. M. {Gambardella} and A. {Giusti}},
  journal={IEEE Robotics and Automation Letters}, 
  title={Learning Visual Localization of a Quadrotor Using its Noise as Self-Supervision}, 
  year={2022},
  volume={7},
  number={2},
  pages={2218-2225},
  doi={10.1109/LRA.2022.3143565}
  }</pre>

  <details>
    <summary>Abstract</summary>
    <p>
    We introduce an approach to train neural network models for visual object localization using a small training set, labeled with ground truth object positions, and a large unlabeled one. We assume that the object to be localized emits sound, which is perceived by a microphone rigidly affixed to the camera. This information is used as the target of a cross-modal pretext task: predicting sound features from camera frames. By solving the pretext task, the model draws self-supervision from visual and auditory data. The approach is well suited to robot learning: we instantiate it to localize a small quadrotor from 128x80 pixel images acquired by a ground robot. Experiments on a separate testing set show that introducing the auxiliary pretext task yields large performance improvements: the Mean Absolute Error (MAE) of the estimated image coordinates of the target is reduced from 7 to 4 pixels; the MAE of the estimated distance is reduced from 28 cm to 14 cm. A model that has access to labels for the entire training set yields a MAE of 2 pixels and 11 cm, respectively.
    </p>
  </details>
  
  <iframe width="854" height="480" src="https://www.youtube.com/embed/fuexj03mGNo" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div>
  <h2>Uncertainty-Aware Self-Supervised Learning of Spatial Perception Tasks</h2>
  <p>
  Mirko Nava, Antonio Paolillo, Jérôme Guzzi, Luca Maria Gambardella, and Alessandro Giusti<br/>
  <i>in IEEE Robotics and Automation Letters, vol. 6, pp. 6693-6700, 2021.</i>
  </p>

  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9477010"><div class="tag pdf">PDF</div></a>
  <a><div class="tag bibtex" onclick="show_bibtex(this)" data-ref="nava2021uncertainty">BIBTEX</div></a>
  <a href="https://doi.org/10.1109/LRA.2021.3095269"><div class="tag doi">DOI</div></a>

  <pre class="bibtex no-scrollbar" data-ref="nava2021uncertainty">@article{nava2021uncertainty,
  author={M. {Nava} and A. {Paolillo} and J. {Guzzi} and L. M. {Gambardella} and A. {Giusti}},
  journal={IEEE Robotics and Automation Letters}, 
  title={Uncertainty-Aware Self-Supervised Learning of Spatial Perception Tasks}, 
  year={2021},
  volume={6},
  number={4},
  pages={6693-6700},
  doi={10.1109/LRA.2021.3095269}
  }</pre>

  <details>
    <summary>Abstract</summary>
    <p>
    We propose a general self-supervised learning approach for spatial perception tasks, such as estimating the pose of an object relative to the robot, from onboard sensor readings. The model is learned from training episodes, by relying on: a continuous state estimate, possibly inaccurate and affected by odometry drift; and a detector, that sporadically provides supervision about the target pose. We demonstrate the general approach in three different concrete scenarios: a simulated robot arm that visually estimates the pose of an object of interest; a small differential drive robot using 7 infrared sensors to localize a nearby wall; an omnidirectional mobile robot that localizes itself in an environment from camera images. Quantitative results show that the approach works well in all three scenarios, and that explicitly accounting for uncertainty yields statistically significant performance improvements.
    </p>
  </details>

  <iframe src="https://www.youtube.com/embed/A9gpNRDH56E" frameborder="0" allow="autoplay; encrypted-media" style="aspect-ratio: 16/9; width: 80%;" allowfullscreen></iframe>
</div>

<div>
  <h2>State-Consistency Loss for Learning Spatial Perception Tasks From Partial Labels</h2>
  <p>
  Mirko Nava, Luca Maria Gambardella, and Alessandro Giusti<br/>
  <i>in IEEE Robotics and Automation Letters, vol. 6, pp. 1112-1119, 2021.</i>
  </p>

  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9345348"><div class="tag pdf">PDF</div></a>
  <a><div class="tag bibtex" onclick="show_bibtex(this)" data-ref="nava2021state">BIBTEX</div></a>
  <a href="https://doi.org/10.1109/LRA.2021.3056378"><div class="tag doi">DOI</div></a>

  <pre class="bibtex no-scrollbar" data-ref="nava2021state">@article{nava2021state,
  author={M. {Nava} and L. M. {Gambardella} and A. {Giusti}},
  journal={IEEE Robotics and Automation Letters}, 
  title={State-Consistency Loss for Learning Spatial Perception Tasks From Partial Labels}, 
  year={2021},
  volume={6},
  number={2},
  pages={1112-1119},
  doi={10.1109/LRA.2021.3056378}
  }</pre>

  <details>
    <summary>Abstract</summary>
    <p>
    When learning models for real-world robot spatial perception tasks, one might have access only to partial labels: this occurs for example in semi-supervised scenarios (in which labels are not available for a subset of the training instances) or in some types of self-supervised robot learning (where the robot autonomously acquires a labeled training set, but only acquires labels for a subset of the output variables in each instance). We introduce a general approach to deal with this class of problems using an auxiliary loss enforcing the expectation that the perceived environment state should not abruptly change; then, we instantiate the approach to solve two robot perception problems: a simulated ground robot learning long-range obstacle mapping as a 400-binary-label classification task in a self-supervised way in a static environment; and a real nano-quadrotor learning human pose estimation as a 3-variable regression task in a semi-supervised way in a dynamic environment. In both cases, our approach yields significant quantitative performance improvements (average increase of 6 AUC percentage points in the former; relative improvement of the R 2 metric ranging from 7% to 33% in the latter) over baselines.
    </p>
  </details>
  <iframe src="https://www.youtube.com/embed/o38QfyoLnUU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div>
  <h2>Learning Long-Range Perception Using Self-Supervision From Short-Range Sensors and Odometry</h2>
  <p>
  Mirko Nava, Jérôme Guzzi, R. Omar Chavez-Garcia, Luca Maria Gambardella and Alessandro Giusti<br/>
  <i>in IEEE Robotics and Automation Letters, vol. 4, pp. 1279-1286, 2019.</i>
  </p>

  <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8624299"><div class="tag pdf">PDF</div></a>
  <a><div class="tag bibtex" onclick="show_bibtex(this)" data-ref="nava2019learning">BIBTEX</div></a>
  <a href="https://doi.org/10.1109/LRA.2019.2894849"><div class="tag doi">DOI</div></a>

  <pre class="bibtex no-scrollbar" data-ref="nava2019learning">@article{nava2019learning, 
  author={M. {Nava} and J. {Guzzi} and R. O. {Chavez-Garcia} and L. M. {Gambardella} and A. {Giusti}},
  journal={IEEE Robotics and Automation Letters}, 
  title={Learning Long-Range Perception Using Self-Supervision From Short-Range Sensors and Odometry}, 
  year={2019}, 
  volume={4}, 
  number={2}, 
  pages={1279-1286}, 
  doi={10.1109/LRA.2019.2894849} 
  }</pre>

  <details>
    <summary>Abstract</summary>
    <p>
    We introduce a general self-supervised approach to predict the future outputs of a short-range sensor (such as a proximity sensor) given the current outputs of a long-range sensor (such as a camera). We assume that the former is directly related to some piece of information to be perceived (such as the presence of an obstacle in a given position), whereas the latter is information rich but hard to interpret directly. We instantiate and implement the approach on a small mobile robot to detect obstacles at various distances using the video stream of the robot's forward-pointing camera, by training a convolutional neural network on automatically-acquired datasets. We quantitatively evaluate the quality of the predictions on unseen scenarios, qualitatively evaluate robustness to different operating conditions, and demonstrate usage as the sole input of an obstacle-avoidance controller. We additionally instantiate the approach on a different simulated scenario with complementary characteristics, to exemplify the generality of our contribution.
    </p>
  </details>

  <iframe src="https://www.youtube.com/embed/w8wzY8wr12k" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>


</body>
</html>
