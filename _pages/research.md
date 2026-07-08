---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My [ORCID Number](http://orcid.org/0000-0001-7586-0142) is 0000-0001-7586-0142. My Google Scholar page is [here](https://scholar.google.com/citations?hl=en&user=heYuqBkAAAAJ).

**Bipedal Robots:** From January 1999 to April 2024, my graduate students and I spearheaded pioneering research that fundamentally transformed feedback control of agile bipedal locomotion. Prior to our efforts, the consensus was that the complexity of models in bipedal robotics made analytical approaches impratical. We discovered that a technique from geometric nonlinear control—specifically, Zero Dynamics—could be applied to these complex hybrid dynamical models with great efficiency. This breakthrough not only enabled us to thoroughly analyze but also to radically enhance the design of feedback algorithms for bipedal robots. By turning traditional methods from nonlinear control on their head and merging them with numerical optimization, we established a robust design methodology now known as Hybrid Zero Dynamics (HZD). This approach has redefined standards in the field, seamlessly integrating theoretical frameworks with practical engineering applications, demonstrated by my team and others on a wide variety of bipedal robots. Our work has significantly advanced the theoretical foundations of the field and has catalyzed innovations in robotic mobility and autonomy.

*   [Papers on biped robots](/publications/robotics.html)
*   [Early Videos Pre-YouTube](robot-videos.html)
*   [Michigan Robotics: Dynamic Legged Locomotion YouTube Channel](http://www.youtube.com/user/DynamicLegLocomotion).
*   [Open-source Software for Estimation and Control](https://github.com/UMich-BipedLab)
*   [Wandercraft](https://en.wandercraft.eu/) The early control laws for Wandercraft's amazing exoskeleton were based on HZD. Thanks to Wandercraft, patients with paraplegia are upright and walking again!
* **Other:** Robots everywhere in our College of Engineering [Michigan Robotics Rocks!](http://www.youtube.com/watch?v=pMaCC__C0cE&feature=c4-overview-vl&list=PL5CFFA0DE541898F8)This is Michigan Engineering [2012](http://www.youtube.com/watch?v=e-p1QiRgxWo&feature=c4-overview-vl&list=PL5CFFA0DE541898F8). Robots are featured widely in UofM media: [Michigan Halftime Video](http://www.youtube.com/watch?v=guj0Ddp4bEA&list=PL5CFFA0DE541898F8) Victors for Michigan Campaign video [short](http://www.youtube.com/watch?v=8C_JpoZeUSk) (MABEL is at 0:16) and [long version](http://www.youtube.com/watch?v=_Mcf4UiaYQA) (MABEL is at 2:01). MABEL goes to the [Field Museum in Chicago.](https://www.youtube.com/watch?v=7qr9zVpqIiw)

<details markdown="1">
<summary><strong>Read more: from nonlinear control to modern legged robotics</strong></summary>

<table>
  <tr>
    <td style="width:50%;vertical-align:top;">
      <img src="/images/RABBIT_in_air.jpg" alt="RABBIT walking experiment" style="width:100%;height:auto;">
      <strong>RABBIT</strong><br>
      A rigid, five-link, four-actuator planar biped for studying underactuation and impacts in walking.
    </td>
    <td style="width:50%;vertical-align:top;">
      <img src="/images/mabel1-big.jpg" alt="MABEL with collaborators" style="width:100%;height:auto;">
      <strong>MABEL</strong><br>
      A compliant bipedal robot that connected HZD ideas to efficient walking and fast running.
    </td>
  </tr>
  <tr>
    <td style="width:50%;vertical-align:top;">
      <img src="/images/slider/MARLO-wavefield-760x400.jpg" alt="MARLO walking outdoors on the Wave Field" style="width:100%;height:auto;">
      <strong>MARLO</strong><br>
      A 3D robot that moved the agenda from planar demonstrations toward outdoor walking.
    </td>
    <td style="width:50%;vertical-align:top;">
      <img src="/images/slider/CassieSmoke2_760x400.jpg" alt="Cassie Blue walking through smoky terrain" style="width:100%;height:auto;">
      <strong>Cassie Blue</strong><br>
      A shared research platform where HZD-style controllers could be tested, compared, and extended.
    </td>
  </tr>
</table>

The contribution of Hybrid Zero Dynamics was not simply that it made robots walk. It gave underactuated walking a mathematical design language. Dynamic legged locomotion involves continuous motion, impacts, changing contacts, underactuation, and stability questions that do not fit neatly into linear time-invariant control. HZD made it possible to design virtual constraints, induce a lower-dimensional invariant dynamics, and analyze periodic motion with tools such as Poincare maps while still respecting the hybrid nature of walking.

That framework mattered because it connected three worlds that are often separated: nonlinear control theory, numerical optimization, and hardware experiments. RABBIT showed that the ideas could survive contact with a physical underactuated robot. MABEL added compliance and dynamic running. MARLO moved toward 3D outdoor walking. Cassie Blue brought the methods onto a platform that many researchers could recognize, reproduce, and compare against.

The later rise of optimization, model predictive control, reinforcement learning, and data-driven locomotion did not replace this earlier work so much as change the surrounding toolchain. Classical nonlinear control supplied structure: models, stability questions, phase variables, virtual constraints, reduced dynamics, and experimentally meaningful benchmarks. Learning-based methods then entered a field where researchers already had better ways to ask what a gait was, how to test it, and how to move from equations to hardware.

In that sense, HZD belongs in the prehistory of modern learning-based legged locomotion. It did not cause the reinforcement-learning revolution, and it did not solve all of locomotion. But it helped make dynamic walking a rigorous engineering problem rather than a collection of impressive demonstrations. It showed that underactuation and impact could be embraced, not hidden, and that mathematical control design could produce controllers that worked on real robots.

This line of work also turned papers into a research ecosystem. The 2007 book *Feedback Control of Dynamic Bipedal Robot Locomotion* organized hybrid models, periodic orbits, virtual constraints, feedback design, and experimental implementation into a form that students and researchers could learn from. Later tools such as FROST and C-FROST helped shorten the path from full-order models to optimized gaits. Students and collaborators carried the methods into new laboratories, newer robot platforms, perception and state estimation, humanoids, exoskeletons, and learning-enhanced locomotion.

The translational thread is also real, though it should be stated with care. Work on lower-limb exoskeletons, including early control work connected to Wandercraft, drew on ideas developed for dynamic bipedal robots. The goal there was not a laboratory demonstration for its own sake, but self-balancing, hands-free locomotion in rehabilitation settings, including for people with paraplegia.

The durable legacy is therefore not a single robot or a single theorem. It is a research pathway: from geometric nonlinear control to hybrid zero dynamics, from analysis to optimization, from simulation to hardware, and from model-based control to the learning-rich methods now shaping legged robotics.

</details>

<br>

**There was a BEFORE BIPED's phase:** I got my start in resarch as an undergraduate at Oklahoma State University in 1977, when Prof. Robert Mulholland recruited me as a research assitant for his work on Modeling the Global Carbon Cycle, a precursor to Climate Modeling.
R. J. Mulholland and J. W. Grizzle, [\`\`Modeling Perturbations of the Global Carbon Cycle,"](/files/GlobalCarbonCycle1979.pdf) _Reprint,_ Proc. of the International Conference on Cybernetics and Society, pp. 690-694, 1979. And yes, it's always been about fossil fuels. Beginning in 1980 at UT Austin, studying under Prof. Steven Marcus, my primary research area became the theory of nonlinear control systems. The work I did on control methods steeped in differential geometry laid the foundations for my later work in bipedal robotics. While I always maintained a strong interest in this subject and felt a sense of community with that body of researchers, my research activities significantly broadened over time. From 1986 to 2010, I worked with my dear friend and colleague, [Jeffrey Cook](https://www.automotivehalloffame.org/honoree/jeffrey-a-cook/), on various aspects of modeling and control of automotive powertrain systems and control; we turned the automotive area into a respecable academic discipline. From 2007 to 2012, I collaborated with [Prof. Huei Peng](https://scholar.google.com/citations?user=MMgcQiIAAAAJ&hl=en)on Hybrid Electric Vehciles (HEVs). From 1991-2001, I applied systems and control techniques to improve the operation of plasma-based microelectronics manufacturing equipment. From 2014 through 2018, I worked with an esteemed group of researchers on correct-by-construction control methods, with the primary application area being Advanced Driver Assist Systems. 

*   [Papers on automotive control](automotive.html)
*   [Papers on nonlinear control theory](control.html)
*   [Papers on semiconductor manufacturing](semiconductor.html)
*   [Models coded in MATLAB](matlab.html)
