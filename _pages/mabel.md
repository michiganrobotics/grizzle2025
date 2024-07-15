---
permalink: /robot-videos/mabel
title: "MABEL"
excerpt: "MABEL the walking robot"
author_profile: true
gallery:
  - url: /mabel1-big.jpg
    image_path: mabel1-big.jpg
    alt: "MABEL late spring"
    title: "MABEL late spring, 2008 (K. Sreenath, H.W. Park, I. Poulakakis, J. Grizzle) "
  - url: /mabel2.jpg
    image_path: mabel2.jpg
    alt: "MABEL contributors"
    title: "Top Row: J. Hurst (CMU), G. Buche (Grenoble), J. Koncsol (GM); Bottom Row: B. Morris (Eaton), S. Zhang (CMU), and RABBIT (Grenoble) all contributed to the test-bed's conception, design, fabrication, and assembly. "

---

{% include gallery %}

### Table of Contents

1.  [Videos](#videos) and [photos](#photos) are available at the bottom of this page.
2.  This work is supported by [NSF](http://nsf.gov/), **the National Science Foundation.**
3.  [Description](#description) of MABEL and what is so [special](#features) about it?
4.  MABEL is planar and has no feet. [Why?](#planar)
5.  Brief statement of our [specific research objectives](#objectives).
6.  Links to SolidWorks Cad files for the robot and much more [robot technical data](#robotdata) are available to the public for free because we are supported by the US National Science Foundation.
7.  Our robotics work has been featured in Scientific American, Discover Magazine, The Economist, and much more.

* * *

**<a name="description"></a>Robot description:** In Summer 2008, we completed assembly of a novel planar bipedal robot for use at the University of Michigan. The robot, named MABEL, was designed in collaboration with Jonathan Hurst, Al Rizzi and Jessica Hodgins of ... [more](/robot-videos/mabel/description.html)

* * *

**<a name="features"></a>Special features:** What is the main difference of the new robot when compared to other robots like ASIMO or QRIO? Is it the ability to be able to walk on uneven terrains or mainly a more efficient way of moving? What will be the real step forward in robot technology? ... [more](/robot-videos/mabel/features.html)

* * *

**<a name="planar"></a>Why planar:** It is important to understand the relevance of research on planar robots with unactuated point feet in the larger context of 3D robots with feet ... [more](/robot-videos/mabel/relevance.html)

* * *

**<a name="objectives"></a>Research objectives:** MABEL was designed to be both a robust walker and a fast runner. It pushes the state of the art in bipedal mechanism design and provides an opportunity for effective control design methodology to maximize the robot's energy efficiency, speed, and stability. Our specific objectives are to demonstrate: energy efficient walking on flat ground; the ability to walk over uneven terrain; and running. All of this should be accomplished with provably correct feedback laws. The emphasis on energy efficiency is because, for a biped to be able to operate in the real world for an extended period of time, it must carry its own power and use that power as economically as possible. The ability to walk on uneven ground will allow bipeds to function out of the laboratory. The ability to run is in part for fun and in part to demonstrate dynamic balance in an extremely challenging situation. The running achieved with current bipeds is very unsatisfactory. Just take a look at their gaits and you'll see what we mean. Finally, the emphasis on provably correct feedback laws is because we are attempting to remove a lot of the trial and error from the process of designing control algorithms for bipedal robots. Our objective is to design controllers on the basis of models and have the controllers work on the associated hardware. It's a big challenge! Maybe the biggest one in the list.

* * *

**<a name="robotdata"></a>Robot Stuff:**

1.  You can download a complete set of CAD files (SolidWorks) for the robot. With these files, you can have all of the parts of the robot machined. [**Click here**](https://mime.engineering.oregonstate.edu/research/drl/publications.html) then scroll to the bottom of the page.
2.  Publications detailing the control laws implemented on the robot are available [**here**](/publications/robotics.html).
3.  A ZIP file providing a symbolic mathematical model of the robot's powertrain is available here. [\[**Right Click and Save**\]](/files/Transmission-Dynamics.zip)
4.  Tons of photographs of the robot's "insides'' are [**here**](#photos).

* * *

**<a name="tours"></a>Lab tours and demos:** We give lab tours, preferably to groups. See contact information above. Bipedal robots have a wide appeal to lay audiences in general, and young students in particular. My graduate students and I have given talks to science camps (all ages and compositions), high school science classes, college clubs, retirement homes, and civic organizations. In each of these settings, we try to take a minute or two in order to discuss feedback and feedback control systems, as well as how pervasive they are in nature and technology.

* * *

**Copyright:** These videos and photos belong to me, my colleagues, and/or my students. You may use them for your own ends as long as you cite their source. If you are a MEDIA outlet, contact us for original, unprocessed HD video.

* * *

### Videos:

1.  **The \*\*most current\*\* MABEL videos are now available on YouTube:** [DynamicLegLocomotion Channel](http://www.youtube.com/user/DynamicLegLocomotion). Because of this, we will update videos on this page less frequently. You can subscribe to the channel for free and have the latest videos at your finger tips!
2.  **(October, 2009) MABEL is operating nicely.** We installed some extra encoders on the robot. The cables in the differential actually stretch more than we ever expected. This causes many problems, as you may expect, if you cannot observe the stretch in your measurements. The additional sensors give us position on motor side and joint side for both knees and hips. Here are some of the cool videos the came out once we improved our measurements.
    1.  [MABEL walking at 1.5 m/s,](https://www.youtube.com/watch?v=FO6Sx2zDURE) which equals 3.4 miles per hour. As of the time of this posting, that makes her the fastest bipedal robot in the world in terms of absolute walking speed.
    2.  [Two-legged hopping.](https://www.youtube.com/watch?v=2GGmBMW0Mdw) This was done to test the accuracy of our dynamic model of MABEL; it's not bad.
    3.  [Compliant Hybrid Zero Dynamics.](https://www.youtube.com/watch?v=PJM1OHm4k74) MABEL walks with the mathematical muscle of the hybrid zero dynamics!
3.  **(July 9, 2009) Back on line and operating.** We were down with power amplifier problems and a number of other hardware issues. We seem to have them resolved. We also conducted parameter identification for the robot and hence we now have a good model for determining (near) optimal trajectories. The pre-loads on the springs have been set to zero. The controllers used in the videos below employ virtual constraints determined from our analytical model. The resulting gaits are MUCH nicer than the gaits obtained with virtual constraints designed by hand. They are also **twice as energy efficient.** Here, the virtual constraints are still implemented via high-gain PD control.
    1.  [MABEL walking at 0.9 m/s](http://www.youtube.com/watch?v=dz_7u2ruNpg&feature=channel_page) taking advantage of the compliance. As stated above, the gait is twice as efficient as a similar gait designed by hand. As has been said many times before, there is nothing more practical than a good theory!
    2.  [Robustness test.](http://www.youtube.com/watch?v=25EBpRYlU7Q&feature=channel_page) MABEL gets pushed around and keeps on walking.
    3.  [Slow Walking.](http://www.youtube.com/watch?v=pq-8yOtiRXE&feature=channel) MABEL's torso is leaned backward by an increasing amount, while all other aspects of the gait remain unchanged, until the robot can no longer continue walking and falls. It is surprising how far back the torso can be leaned.
    4.  [Hand-designed virtual constraints.](http://www.youtube.com/watch?v=oiDsffH-BKs&feature=channel) This video is from August 8, 2008. Compare the gait here to any of the gaits in the above newer videos. In addition to not looking pretty, it is less energy efficient by a factor of two.
4.  **(August 8, 2008) A few nice laps to show that the robot is functional.** We programmed a controller using hand-tuned virtual constraints because we have not finished identifying the center of mass and inertia parameters of the robot. For the first video, pre-tensions on the springs were set, effectively removing the springs from the powertrain. In the second video, the pre-tensions are removed, so the springs are absorbing the impact forces. They make a significant difference. Note that a "falling" video is included to show that the bar does not hold up the robot. This incident occurred when we inadvertently severed a communication cable.
    1.  Walking at 1.2 m/s, without taking advantage of the compliance: [High Def for PC (Big but worth it at 148.6MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/MABLE_walking1pt2m_per_second_HD.wmv) and [MAC (12.7MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/MABLE_walking1pt2m_per_second.mov)
    2.  Walking at 0.98 m/s, this time taking advantage of the compliance [High Def for PC (Big but worth it at 157MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/MABLE_walking0pt98m_per_second_HD.wmv) and [MAC (13.4MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/MABLE_walking0pt98m_per_second.mov)
    3.  Falling due to a severed cable [PC (8MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/falling.wmv)
5.  **(November 2007) The construction of the bipedal test bed included several phases.** The videos below show the assembly process of the robot itself, once fabrication was complete. The videos are meant to be fun; they are not all that informative! The fabrication of the electronics and the composition of the code for the real-time control system are less visual and are not shown. Those parts took a long time. The videos are only posted in a form compatible for PCs (.wmv).
    1.  [Video 1 (20.5MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/video1.wmv) and [Video 2 (21.0MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/video2.wmv) and [Video 3 (21.2MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/video3.wmv) and [Video 4 (21.4MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/video4.wmv) and [Video 5 (9.8MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/video5.wmv)
    2.  [Compilation of Assembly (29.6MB)](http://websites.umich.edu/~grizzlefacultyafs/vids/FullAssembly.wmv)

* * *

### Photos
(the files are large; you should right click and save to your hard drive before opening them)**

1.  [MABEL with shadow and no background](http://websites.umich.edu/~grizzlefacultyafs/images/MABEL13Nov2010.tif)
2.  [During a Demo on 09 July 2009 (zipped)](http://websites.umich.edu/~grizzlefacultyafs/images/PhotosMABEL09July2009.zip)
3.  [Senator Carl Levin visits our booth on 11 August 2008 (zipped)](http://websites.umich.edu/~grizzlefacultyafs/images/PhotosMABEL_SenatorLevin11August2008.zip)
4.  [MABEL Photos 28 and 29 July 2008 (zipped)](http://websites.umich.edu/~grizzlefacultyafs/images/MABEL_29July2008.zip)
5.  [MABEL Photos 15 March 2008 (zipped)](http://websites.umich.edu/~grizzlefacultyafs/images/PhotosMABEL15March2008.zip)
6.  [MABEL Photos 8 December 2007 (zipped)](http://websites.umich.edu/~grizzlefacultyafs/images/MABEL_Photos8December2007.zip)
7.  [MABEL Photos 10 Nov 2007 (zipped)](http://websites.umich.edu/~grizzlefacultyafs/images/MabelPhotos10Nov2007.zip)