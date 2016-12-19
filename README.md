# 持续更新修改中
2016.12.19
# SlamList
===========================================
##Contents
- [Tutorials-SLAM](#Tutorials-SLAM)
- [Papers-SLAM](#Papers-SLAM)
- [OpenSource-SLAM](#OpenSource-SLAM)
- [Feature detection description](#Features)
- [Datasets with ground truth - Reproducible research](#Dataset)
- [License](#license)
- [Contributing](#contributing)

<a name="Tutorials-SLAM"></a>
# Tutorials-SLAM

## SLAM Tutorial & survey

[ICRA 2016 Aerial Robotics - (Visual odometry)](http://mrsl.grasp.upenn.edu/loiannog/tutorial_ICRA2016/VO_Tutorial.pdf) D. Scaramuzza

[Simultaneous Localization And Mapping: Present, Future, and the Robust-Perception Age](http://arxiv.org/pdf/1606.05830.pdf). C. Cadena, L. Carlone, H. Carrillo, Y. Latif, D. Scaramuzza, J. Neira, I. D. Reid, J. J. Leonard. "The paper summarizes the outcome of the workshop “The Problem of Mobile Sensors: Setting future goals and indicators of progress for SLAM” held during the Robotics: Science and System (RSS) conference (Rome, July 2015)."


[Visual Odometry: Part I - The First 30 Years and Fundamentals](http://rpg.ifi.uzh.ch/docs/VO_Part_I_Scaramuzza.pdf), D. Scaramuzza and F. Fraundorfer, IEEE Robotics and Automation Magazine, Volume 18, issue 4, 2011

[Visual Odometry: Part II - Matching, robustness, optimization, and applications](http://rpg.ifi.uzh.ch/docs/VO_Part_II_Scaramuzza.pdf), F. Fraundorfer and D. Scaramuzza, IEEE Robotics and Automation Magazine, Volume 19, issue 2, 2012

## Computer vision books

[Computer Vision: Algorithms and Applications](http://szeliski.org/Book/). R. Szeliski. 2010.

## Video
视觉SLAM十四讲
[视觉SLAM十四讲：https://github.com/gaoxiang12](https://github.com/gaoxiang12)<br />

<a name="Papers-SLAM"></a>
#Papers-SLAM
## SLAM/VO

### Visual odometry (image based only)

[Real-time simultaneous localisation and mapping with a single camera](https://www.doc.ic.ac.uk/~ajd/Publications/davison_iccv2003.pdf). A. J. Davison. ICCV 2003.

[Visual odometry](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.137.4025&rep=rep1&type=pdf). D. Nister, O. Naroditsky, and J. Bergen. CVPR 2004.

[Real time localization and 3d reconstruction](http://maxime.lhuillier.free.fr/pCvpr06.pdf). E. Mouragnon, M. Lhuillier, M. Dhome, F. Dekeyser, and P. Sayd. CVPR 2006.

[Parallel Tracking and Mapping for Small AR Workspaces](http://www.robots.ox.ac.uk/~gk/publications/KleinMurray2007ISMAR.pdf). G. Klein, D. Murray. ISMAR 2007.

[Real-Time 6-DOF Monocular Visual SLAM in a Large-scale Environments](http://cvlab.hanyang.ac.kr/~jwlim/files/icra2014vslam.pdf). H. Lim, J. Lim, H. Jin Kim. ICRA 2014.

<a name="OpenSource-SLAM"></a>
# OpenSource-SLAM
<div>
     <table border="0">
	  <tr>
	    <th> Project </th>
	    <th> Sensor </th>
	    <th> Link </th>
	    <th> Other </th>
	    <th> Language </th>
	    <th> License </th>
	  </tr>
	  <tr>
	    <td>MonSLAM</td>
	    <td>单目</td>
	    <td>https://github.com/hanmekim/SceneLib2</td>
	    <td>https://github.com/OpenSLAM/SceneLib2</td>
	  </tr>
	  <tr>
	    <td>PTAM</td>
	    <td>单目</td>
	    <td>https://www.robots.ox.ac.uk/~gk/PTAM</td>
	    <td>https://github.com/OpenSLAM/PTAM-GPL</td>
	  </tr>
	  <tr>
	    <td>ORB-SLAM</td>
	    <td>单目为主</td>
	    <td>http://webdiis.unizar.es/~raulmur/orbslam</td>
	    <td>https://github.com/OpenSLAM/ORB_SLAM</td>
	    <td> C++ </td>
	    <td> GPLv3 </td>
	  </tr>
	  <tr>
	    <td>LSD-SLAM</td>
	    <td>单目为主</td>
	    <td>http://vision.in.tum.de/research/vslam/lsdslam</td>
	    <td>https://github.com/OpenSLAM/lsd_slam</td>
	    <td> C++/ROS </td>
	    <td> GNU General Public License </td>
	  </tr>
	  <tr>
	    <td>SVO</td>
	    <td>单目</td>
	    <td>https://github.com/uzh-rpg/rpg_svo</td>
	    <td>https://github.com/OpenSLAM/rpg_svo</td>
	    <td> C++/ROS </td>
	    <td> GNU General Public License </td>
	  </tr>
	  <tr>
	    <td>DTAM</td>
	    <td>RGB-D</td>
	    <td>https://github.com/anuranbaka/OpenDTAM</td>
	    <td>https://github.com/OpenSLAM/OpenDTAM</td>
	  </tr>
	  <tr>
	    <td>DVO</td>
	    <td>RGB-D</td>
	    <td>https://github.com/tum-vision/dvo_slam</td>
	    <td>https://github.com/OpenSLAM/dvo_slam</td>
	  </tr>
	  <tr>
	    <td>DSO</td>
	    <td>单目</td>
	    <td>https://github.com/JakobEngel/dso</td>
	    <td>https://github.com/OpenSLAM/dso</td>
	  </tr>
	  <tr>
	    <td>RTAB-MAP</td>
	    <td>双目/RGB-D</td>
	    <td>https://github.com/introlab/rtabmap</td>
	    <td>https://github.com/OpenSLAM/rtabmap </td>
	  </tr>
	  <tr>
	    <td>RGBD-SLAM-V2</td>
	    <td>RGB-D</td>
	    <td>https://github.com/felixendres/rgbdslam_v2</td>
	    <td>https://github.com/OpenSLAM/rgbdslam_v2</td>
	  </tr>
	  <tr>
	    <td>Elastic Fusion</td>
	    <td>RGB-D</td>
	    <td>https://github.com/mp3guy/ElasticFusion</td>
	    <td>https://github.com/OpenSLAM/ElasticFusion</td>
	  </tr>
	  <tr>
	    <td>Hector SLAM</td>
	    <td>激光</td>
	    <td>https://wiki.ros.org/hector_slam</td>
	    <td></td>
	  </tr>
	  <tr>
	    <td>GMapping</td>
	    <td>激光</td>
	    <td>https://wiki.ros.org/gmapping</td>
	    <td></td>
	  </tr>
	  <tr>
	    <td>OKVIS</td>
	    <td>多目+IMU</td>
	    <td>https://github.com/ethz-asl/okvis</td>
	    <td>https://github.com/OpenSLAM/okvis</td>
	  </tr>
	  <tr>
	    <td>ROVIO</td>
	    <td>多目+IMU</td>
	    <td>https://github.com/ethz-asl/rovio</td>
	    <td>https://github.com/OpenSLAM/rovio</td>
	  </tr>
	  <tr>
	    <td> COSLAM </td>
	    <td>  </td>
	    <td>http://drone.sjtu.edu.cn/dpzou/project/coslam.php</td>
	    <td>https://github.com/OpenSLAM/rovio</td>
	    <td> C++ </td>
	    <td> GNU General Public License </td>
	  </tr>
	  <tr>
	    <td> DTSLAM </td>
	    <td>  </td>
	    <td>https://github.com/plumonito/dtslam</td>
	    <td>  </td>
	    <td> C++ </td>
	    <td> modified BSD </td>
	  </tr>
	  <tr>
	    <td> REBVO </td>
	    <td>  </td>
	    <td>https://github.com/JuanTarrio/rebvo</td>
	    <td>  </td>
	    <td> C++ </td>
	    <td> GNU General Public License </td>
	  </tr>
	</table>
</div>

<a name="opensource-minimization"></a>
## OpenSource minimization

| Project |  Language | License |
| ---  | --- | --- |
|[CERES SOLVER](https://github.com/ceres-solver/ceres-solver) | C++ | BSD License|
|[GTSAM](https://collab.cc.gatech.edu/borg/gtsam) | C++ | BSD License|
|[G2O](https://github.com/RainerKuemmerle/g2o) | C++ |  BSD License + L/GPL3 restriction|
|[NLOPT](http://ab-initio.mit.edu/wiki/index.php/NLopt) | C++ | LGPL|

## 更新中

1.泡泡机器人SLAM 微信公众号：paopaorobot_slam

2.[高翔博士：https://github.com/gaoxiang12](https://github.com/gaoxiang12)<br />