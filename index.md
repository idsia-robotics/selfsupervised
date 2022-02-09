---
layout: splash
title: Research on Human-Robot Interaction using Pointing Gestures
header:
  image: /proximity-hri-pipeline/img/overview.jpg
  caption: >-
    Photo credit: 
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

Humans use pointing gestures extensively when they communicate with other nearby humans, mainly to indicate positions, directions or objects in the shared space.  This page summarizes recent research at IDSIA, exploring methods to achieve the same interaction modality using a wearable bracelet as a sensor; the method is applied to various robot systems, including drones and large conveyor-belt plants used for logistics.
</div>
<div markdown="1">

# Publications

## Interacting with a Conveyor Belt in Virtual Reality using Pointing Gestures

J. Guzzi, G. Abbate, A. Paolillo, and A. Giusti<br/>
_HRI2022 Demo, to appear_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/guzzi2022demo.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #guzzi2022demo-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #guzzi2022demo-bibtex, #guzzi2022demo-show {
      display: none;
  }
</style>

<input type="checkbox" id="guzzi2022demo-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="guzzi2022demo-show"><span class="csl-label">BIBTEX</span></label>
</div>

<div id="guzzi2022demo-bibtex">
  <p></p>
  <pre>
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We present an interactive demonstration where users are immersed in a virtual reality simulation of a logistic automation system. Using pointing gestures sensed by wrist-worn inertial measurement unit, users select defective packages transported on conveyor belts. The demonstration allows users to experience a novel way to interact with automation systems, and shows an effective application of virtual reality for human-robot interaction studies.</p>
</details>

<div class="video-container">
        <video width="100%" controls>
          <source src="files/videos/guzzi2022demo.mp4" type="video/mp4" />
        </video>
</div>
</div>

<div markdown="1">

## PointIt: A ROS Toolkit for Interacting with Co-located Robots using Pointing Gestures

G. Abbate, A. Giusti, A. Paolillo, B. Gromov, L. Gambardella, A. Rizzoli, and J. Guzzi<br/>
_HRI2022 Short Contribution, to appear_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/abbate2022short.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #abbate2022short-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #abbate2022short-bibtex, #abbate2022short-show {
      display: none;
  }
</style>

<input type="checkbox" id="abbate2022short-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="abbate2022short-show"><span class="csl-label">BIBTEX</span></label>
</div>


<div class="csl-details"><a href="https://github.com/Gabry993/pointing-user-interface-hri">DETAILS</a></div>

<div id="abbate2022short-bibtex">
  <p></p>
  <pre>
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We introduce PointIt, a toolkit for the Robot Operating System (ROS2) to build human-robot interfaces based on pointing gestures sensed by a wrist-worn Inertial Measurement Unit, such as a smartwatch.  We release the software as open-source with MIT license; docker images and exhaustive instructions simplify its usage in simulated and real-world deployments.</p>
</details>
</div>

<div markdown="1">

## IMU-based pointing for package selection on industrial conveyor belts

G. Abbate, A. Giusti, A. Paolillo, L. Gambardella, A. Rizzoli, and J. Guzzi
</div>
<div>
<!-- <div class="csl-pdf"><a href="{{'/files/guzzi2022demo.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #guzzi2022demo-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #guzzi2022demo-bibtex, #guzzi2022demo-show {
      display: none;
  }
</style>

<input type="checkbox" id="guzzi2022demo-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="guzzi2022demo-show"><span class="csl-label">BIBTEX</span></label>
</div> -->


<div class="csl-details"><a href="https://github.com/idsia-robotics/pointing-belts">DETAILS</a></div>

<!-- <div id="guzzi2022demo-bibtex">
  <p></p>
  <pre>
</pre>
</div> -->

<details>
  <summary>Abstract</summary>
  <p>
  We introduce an intuitive pointing-based interface to select objects moving on a system of conveyor belts. The interface has minimal sensing requirements, as the operator only needs to wear an Inertial Measurement Unit on the wrist (e.g., a smartwatch). LED strips provide the required visual feedback to precisely point to the objects and select them. We experimentally compare the proposed approach with a baseline mouse-based graphical user interface in which the user can click on packages with a mouse. Quantitative results show that our interface compares favorably to the baseline, especially in difficult scenarios involving many packages moving fast.</p>
</details>

<iframe width="560" height="315" src="https://www.youtube.com/embed/hB33cX6pvmg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/3J1HDkwa8qU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div markdown="1">

## Pointing at Moving Robots: Detecting Events from Wrist IMU Data

G. Abbate, B. Gromov, L. Gambardella, and A. Giusti<br/>
_in 2021 IEEE International Conference on Robotics and Automation (ICRA), pp. 3604-3611, 2021_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/abbate2021moving.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #abbate2021moving-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #abbate2021moving-bibtex, #abbate2021moving-show {
      display: none;
  }
</style>

<input type="checkbox" id="abbate2021moving-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="abbate2021moving-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1109/ICRA48506.2021.9561387" onclick="outbound_link('https://doi.org/10.1109/ICRA48506.2021.9561387'); return false;">DOI</a></div>

<div id="abbate2021moving-bibtex">
  <p></p>
  <pre>@INPROCEEDINGS{9561387,
  author={Abbate, Gabriele and Gromov, Boris and Gambardella, Luca M. and Giusti, Alessandro},
  booktitle={2021 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={Pointing at Moving Robots: Detecting Events from Wrist IMU Data}, 
  year={2021},
  volume={},
  number={},
  pages={3604-3611},
  doi={10.1109/ICRA48506.2021.9561387}}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We propose a practical approach for detecting the event that a human wearing an IMU-equipped bracelet points at a moving robot; the approach uses a learned classifier to verify if the robot motion (as measured by its odometry) matches the wrist motion, and does not require that the relative pose of the operator and robot is known in advance. To train the model and validate the system, we collect datasets containing hundreds of real-world pointing events. Extensive experiments quantify the performance of the classifiers and relevant metrics of the resulting detectors; the approach is implemented in a real-world demonstrator that allows users to land quadrotors by pointing at them.</p>
</details>

<iframe width="560" height="315" src="https://www.youtube.com/embed/x7Xt7Xr7pWk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div markdown="1">

## Intuitive 3D Control of a Quadrotor in User Proximity with Pointing Gestures

B. Gromov, J. Guzzi, L. Gambardella, and A. Giusti<br/>
_in 2020 IEEE International Conference on Robotics and Automation (ICRA), 2020, pp. 5964-5971_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2020intuitive.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2020intuitive-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2020intuitive-bibtex, #gromov2020intuitive-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2020intuitive-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2020intuitive-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1109/ICRA40945.2020.9196654" onclick="outbound_link('https://doi.org/10.1109/ICRA40945.2020.9196654'); return false;">DOI</a></div>
<div class="csl-details"><a href="{{'/3d-pointing/index.html'| relative_url }}">DETAILS</a></div>

<div id="gromov2020intuitive-bibtex">
  <p></p>
  <pre>@INPROCEEDINGS{gromov2020intuitive,
  author={Gromov, Boris and Guzzi, Jérôme and Gambardella, Luca M. and Giusti, Alessandro},
  booktitle={2020 IEEE International Conference on Robotics and Automation (ICRA)}, 
  title={Intuitive 3D Control of a Quadrotor in User Proximity with Pointing Gestures}, 
  year={2020},
  volume={},
  number={},
  pages={5964-5971},
  doi={10.1109/ICRA40945.2020.9196654}
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We present an approach for controlling the position of a quadrotor in 3D space using pointing gestures; the task
is difficult because it is in general ambiguous to infer where,
along the pointing ray, the robot should go. We propose and
validate a pragmatic solution based on a push button acting as a
simple additional input device which switches between different
virtual workspace surfaces. Results of a study involving ten
subjects show that the approach performs well on a challenging
3D piloting task, where it compares favorably with joystick
control.</p>
</details>

<iframe src="https://www.youtube.com/embed/9PeCe9AVh-4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div markdown="1">

## Guiding Quadrotor Landing with Pointing Gestures

B. Gromov, L. Gambardella, and A. Giusti<br/>
_in Human-Friendly Robotics 2019, Cham, 2020, pp. 1–14_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2020guiding.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2020guiding-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2020guiding-bibtex, #gromov2020guiding-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2020guiding-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2020guiding-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1007/978-3-030-42026-0_1" onclick="outbound_link('https://doi.org/10.1007/978-3-030-42026-0_1'); return false;">DOI</a></div>
<div class="csl-details"><a href="{{'/hri-landing/index.html'| relative_url }}">DETAILS</a></div>
<div id="gromov2020guiding-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2020guiding,
  author = {Gromov, Boris and Gambardella, Luca and Giusti, Alessandro},
  editor = {Ferraguti, Federica and Villani, Valeria and Sabattini, Lorenzo and Bonf{\`e}, Marcello},
  title = {Guiding Quadrotor Landing with Pointing Gestures},
  booktitle = {Human-Friendly Robotics 2019},
  year = {2020},
  month = feb,
  publisher = {Springer International Publishing},
  address = {Cham},
  pages = {1--14},
  isbn = {978-3-030-42026-0},
  doi = {10.1007/978-3-030-42026-0_1},
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
   We present a system which allows an operator to land a
quadrotor on a precise spot in its proximity by only using pointing gestures; the system has very limited requirements in terms of robot capabilities, relies on an unobtrusive bracelet-like device worn by the operator,
and depends on proven, field-ready technologies. During the interaction,
the robot continuously provides feedback by controlling its position in
real time: such feedback has a fundamental role in mitigating sensing inaccuracies and improving user experience. We report a user study where
our approach compares well with a standard joystick-based controller in
terms of intuitiveness (amount of training required), landing spot accuracy, and efficiency.</p>
</details>
</div>
<div markdown="1">

## Proximity Human-Robot Interaction Using Pointing Gestures and a Wrist-mounted IMU

B. Gromov, G. Abbate, L. Gambardella, and A. Giusti<br/>
_in 2019 IEEE International Conference on Robotics and Automation (ICRA), 2019, pp. 8084–8091_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2019proximity.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2019proximity-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2019proximity-bibtex, #gromov2019proximity-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2019proximity-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2019proximity-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1109/ICRA.2019.8794399" onclick="outbound_link('https://doi.org/10.1109/ICRA.2019.8794399'); return false;">DOI</a></div>
<div class="csl-details"><a href="{{'/proximity-hri-pipeline/index.html'| relative_url }}">DETAILS</a></div>

<div id="gromov2019proximity-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2019proximity,
  author = {Gromov, Boris and Abbate, Gabriele and Gambardella, Luca and Giusti, Alessandro},
  title = {Proximity Human-Robot Interaction Using Pointing Gestures and a Wrist-mounted {IMU}},
  booktitle = {2019 IEEE International Conference on Robotics and Automation (ICRA)},
  pages = {8084-8091},
  year = {2019},
  month = may,
  doi = {10.1109/ICRA.2019.8794399},
  issn = {2577-087X},
  video = {https://youtu.be/hyh_5A4RXZY},
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
   We present a system for interaction between colocated humans and mobile robots, which uses pointing gestures
sensed by a wrist-mounted IMU. The operator begins by
pointing, for a short time, at a moving robot. The system
thus simultaneously determines: that the operator wants to
interact; the robot they want to interact with; and the relative
pose among the two. Then, the system can reconstruct pointed
locations in the robot’s own reference frame, and provide
real-time feedback about them so that the user can adapt
to misalignments. We discuss the challenges to be solved to
implement such a system and propose practical solutions,
including variants for fast flying robots and slow ground robots.
We report different experiments with real robots and untrained
users, validating the individual components and the system as
a whole.</p>
</details>
<iframe width="560" height="315" src="https://www.youtube.com/embed/hyh_5A4RXZY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

</div>

<div markdown="1">

## Video: Pointing Gestures for Proximity Interaction

B. Gromov, J. Guzzi, G. Abbate, L. Gambardella, and A. Giusti<br/>
_in HRI ’19: 2019 ACM/IEEE International Conference on Human-Robot Interaction, March 11–14, 2019, Daegu, Rep. of Korea, 2019_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2019demo.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2019demo-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2019demo-bibtex, #gromov2019demo-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2019demo-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2019demo-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1109/HRI.2019.8673020" onclick="outbound_link('https://doi.org/10.1109/HRI.2019.8673020'); return false;">DOI</a></div>
<div class="csl-award"><a href="{{'/pointing-gestures/gromov2019video-award.jpg'| relative_url }}">AWARD</a></div>
<div class="csl-details"><a href="{{'/pointing-gestures/index.html'| relative_url }}">DETAILS</a></div>
<div id="gromov2019demo-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2019video,
  author = {Gromov, Boris and Guzzi, J{\'e}r{\^o}me and Abbate, Gabriele and Gambardella, Luca and Giusti, Alessandro},
  title = {Video: Pointing Gestures for Proximity Interaction},
  booktitle = {HRI~'19: 2019 ACM/IEEE International Conference on Human-Robot Interaction, March 11--14, 2019, Daegu, Rep. of Korea},
  conference = {2019 ACM/IEEE International Conference on Human-Robot Interaction},
  location = {Daegu, Rep. of Korea},
  year = {2019},
  month = mar,
  video = {https://youtu.be/yafy-HZMk_U},
  doi = {10.1109/HRI.2019.8673020},
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We demonstrate a system to control robots in the users proximity with pointing gestures-a natural device that people use all the time to communicate with each other. Our setup consists of a miniature quadrotor Crazyflie 2.0, a wearable inertial measurement unit MetaWearR+ mounted on the user's wrist, and a laptop as the ground control station.</p>
</details>
<iframe width="560" height="315" src="https://www.youtube.com/embed/yafy-HZMk_U" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div markdown="1">

## Demo: Pointing Gestures for Proximity Interaction

B. Gromov, J. Guzzi, L. Gambardella, and A. Giusti<br/>
_in HRI ’19: 2019 ACM/IEEE International Conference on Human-Robot Interaction, March 11–14, 2019, Daegu, Rep. of Korea, 2019_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2019demo.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2019demo-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2019demo-bibtex, #gromov2019demo-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2019demo-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2019demo-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1109/HRI.2019.8673329" onclick="outbound_link('https://doi.org/10.1109/HRI.2019.8673329'); return false;">DOI</a></div>
<div class="csl-award"><a href="{{'/pointing-gestures/gromov2019demo-award.jpg'| relative_url }}">AWARD</a></div>
<div id="gromov2019demo-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2019demo,
  author = {Gromov, Boris and Guzzi, J{\'e}r{\^o}me and Gambardella, Luca and Giusti, Alessandro},
  title = {Demo: Pointing Gestures for Proximity Interaction},
  booktitle = {HRI~'19: 2019 ACM/IEEE International Conference on Human-Robot Interaction, March 11--14, 2019, Daegu, Rep. of Korea},
  conference = {2019 ACM/IEEE International Conference on Human-Robot Interaction},
  location = {Daegu, Rep. of Korea},
  year = {2019},
  month = mar,
  doi = {10.1109/HRI.2019.8673329},
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We demonstrate a system to control robots in the users proximity with pointing gestures-a natural device that people use all the time to communicate with each other. Our setup consists of a miniature quadrotor Crazyflie 2.0, a wearable inertial measurement unit MetaWearR+ mounted on the user's wrist, and a laptop as the ground control station.</p>
</details>
</div>

<div markdown="1">

## Robot Identification and Localization with Pointing Gestures

B. Gromov, L. Gambardella, and A. Giusti<br/>
_in 2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2018, pp. 3921–3928_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2018robot.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2018robot-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2018robot-bibtex, #gromov2018robot-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2018robot-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2018robot-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1109/IROS.2018.8594174" onclick="outbound_link('https://doi.org/10.1109/IROS.2018.8594174'); return false;">DOI</a></div>
<div class="csl-details"><a href="{{'/motion-relloc/index.html'| relative_url }}">DETAILS</a></div>

<div id="gromov2018robot-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2018robot,
  author = {Gromov, Boris and Gambardella, Luca and Giusti, Alessandro},
  title = {Robot Identification and Localization with Pointing Gestures},
  booktitle = {2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year = {2018},
  pages = {3921-3928},
  keywords = {Robot sensing systems;Robot kinematics;Solid modeling;Manipulators;Drones;Three-dimensional displays},
  doi = {10.1109/IROS.2018.8594174},
  issn = {2153-0866},
  month = oct,
  video = {https://youtu.be/VaQ3aZBf_uE},
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We propose a novel approach to establish the
relative pose of a mobile robot with respect to an operator that
wants to interact with it; we focus on scenarios in which the
robot is in the same environment as the operator, and is visible
to them. The approach is based on comparing the trajectory of
the robot, which is known in the robot’s odometry frame, to the
motion of the arm of the operator, who, for a short time, keeps
pointing at the robot they want to interact with. In multi-robot
scenarios, the same approach can be used to simultaneously
identify which robot the operator wants to interact with. The
main advantage over alternatives is that our system only relies
on the robot’s odometry, on a wearable inertial measurement
unit (IMU), and, crucially, on the operator’s own perception.
We experimentally show the feasibility of our approach using
real-world robots.</p>
</details>

<iframe width="560" height="315" src="https://www.youtube.com/embed/VaQ3aZBf_uE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

</div>

<div markdown="1">

## Video: Landing a Drone with Pointing Gestures

B. Gromov, L. Gambardella, and A. Giusti<br/>
_in HRI ’18 Companion: 2018 ACM/IEEE International Conference on Human-Robot Interaction Companion, March 5–8, 2018, Chicago, IL, USA, 2018_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2018video.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2018video-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2018video-bibtex, #gromov2018video-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2018video-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2018video-show"><span class="csl-label">BIBTEX</span></label>
</div>
<div class="csl-doi"><a href="https://doi.org/10.1145/3173386.3177530" onclick="outbound_link('https://doi.org/10.1145/3173386.3177530'); return false;">DOI</a></div>
<div class="csl-details"><a href="{{'/hri-landing/index.html'| relative_url }}">DETAILS</a></div>

<div id="gromov2018video-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2018video,
  author = {Gromov, Boris and Gambardella, Luca and Giusti, Alessandro},
  title = {Video: Landing a Drone with Pointing Gestures},
  booktitle = {HRI~'18 Companion: 2018 ACM/IEEE International Conference on Human-Robot Interaction Companion, March 5--8, 2018, Chicago, IL, USA},
  conference = {2018 ACM/IEEE International Conference on Human-Robot Interaction Companion},
  doi = {10.1145/3173386.3177530},
  isbn = {978-1-4503-5615-2/18/03},
  location = {Chicago, IL, USA},
  year = {2018},
  month = mar,
  acmid = {3177530},
  publisher = {ACM},
  video = {https://youtu.be/jpG8Jsmth2Y},
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We demonstrate an intuitive gesture-based interface for manually
guiding a drone to land on a precise spot. Using unobtrusive wearable sensors, an operator can quickly and accurately maneuver and
land the drone after very little training; a preliminary user study
on 5 subjects shows that the system compares favorably with a
traditional joystick interface.</p>
</details>

<iframe width="560" height="315" src="https://www.youtube.com/embed/jpG8Jsmth2Y" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div markdown="1">

## Learning to detect pointing gestures from wearable IMUs

D. Broggini, B. Gromov, L. M. Gambardella, and A. Giusti<br/>
_in Proceedings of Thirty-Second AAAI Conference on Artificial Intelligence, February 2-7, 2018, New Orleans, Louisiana, USA, 2018_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/broggini2018learning.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #broggini2018learning-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #broggini2018learning-bibtex, #broggini2018learning-show {
      display: none;
  }
</style>

<input type="checkbox" id="broggini2018learning-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="broggini2018learning-show"><span class="csl-label">BIBTEX</span></label>
</div>

<div id="broggini2018learning-bibtex">
  <p></p>@inproceedings{broggini2018learning,
  author = {Broggini, Denis and Gromov, Boris and Gambardella, Luca M. and Giusti, Alessandro},
  title = {Learning to detect pointing gestures from wearable {IMUs}},
  booktitle = {Proceedings of Thirty-Second {AAAI} Conference on Artificial Intelligence, February 2-7, 2018, New Orleans, Louisiana, {USA}},
  year = {2018},
  month = feb,
  publisher = { {AAAI} Press},
  url = {https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16259/16463},
}
  <pre>
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
  We propose a learning-based system for detecting when a
user performs a pointing gesture, using data acquired from
IMU sensors, by means of a 1D convolutional neural network.
We quantitatively evaluate the resulting detection accuracy,
and discuss an application to a human-robot interaction task
where pointing gestures are used to guide a quadrotor landing.</p>
</details>

</div>

<div markdown="1">

## Wearable multi-modal interface for human multi-robot interaction

 B. Gromov, L. M. Gambardella, and G. A. Di Caro<br/>
_in Safety, Security, and Rescue Robotics (SSRR), 2016 IEEE International Symposium on, 2016, pp. 240–245_
</div>
<div>
<div class="csl-pdf"><a href="{{'/files/gromov2016wearable.pdf'| relative_url }}">PDF</a></div>

<style type="text/css">
  input[type='checkbox']:checked ~ #gromov2016wearable-bibtex {
      display: block;
  }

  input[type='checkbox'] ~ #gromov2016wearable-bibtex, #gromov2016wearable-show {
      display: none;
  }
</style>

<input type="checkbox" id="gromov2016wearable-show" />
<div class="csl-bibtex">
  <label class="csl-label" for="gromov2016wearable-show"><span class="csl-label">BIBTEX</span></label>
</div>

<div class="csl-doi"><a href="https://doi.org/10.1109/SSRR.2016.7784305" onclick="outbound_link('https://doi.org/10.1109/SSRR.2016.7784305'); return false;">DOI</a></div>

<div id="gromov2016wearable-bibtex">
  <p></p>
  <pre>@inproceedings{gromov2016wearable,
  title = {Wearable multi-modal interface for human multi-robot interaction},
  author = {Gromov, Boris and Gambardella, Luca M and Di Caro, Gianni A},
  booktitle = {Safety, Security, and Rescue Robotics (SSRR), 2016 IEEE International Symposium on},
  pages = {240--245},
  year = {2016},
  organization = {IEEE},
  doi = {10.1109/SSRR.2016.7784305},
  video = {https://youtu.be/FWMCxARQYhY}
}
</pre>
</div>

<details>
  <summary>Abstract</summary>
  <p>
A complete prototype for multi-modal interaction
between humans and multi-robot systems is described. The
application focus is on search and rescue missions. From the
human-side, speech and arm and hand gestures are combined
to select, localize, and communicate task requests and spatial
information to one or more robots in the field. From the robot
side, LEDs and vocal messages are used to provide feedback
to the human. The robots also employ coordinated autonomy
to implement group behaviors for mixed initiative interaction.
The system has been tested with different robotic platforms
based on a number of different useful interaction patterns.</p>
</details>
<iframe width="560" height="315" src="https://www.youtube.com/embed/FWMCxARQYhY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

  </body>

</html>
