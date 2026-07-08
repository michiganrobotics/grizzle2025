---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My [ORCID Number](http://orcid.org/0000-0001-7586-0142) is 0000-0001-7586-0142. My Google Scholar page is [here](https://scholar.google.com/citations?hl=en&user=heYuqBkAAAAJ).

**Bipedal Robots:** From January 1999 to April 2024, my graduate students, collaborators, and I worked on feedback control of agile bipedal locomotion. The central idea was to treat dynamic walking and running as a problem in hybrid nonlinear control: continuous motion between foot impacts, discrete events at contact, underactuation, stability of periodic motion, and feedback laws that could be analyzed and implemented on physical machines.

At the start of this work, many researchers viewed the full models of bipedal robots as too complex for analytical feedback design. We found that zero dynamics, a technique from geometric nonlinear control, could be adapted to hybrid models of walking robots and combined with numerical optimization. This became known as Hybrid Zero Dynamics, or HZD.

What made the approach useful was not only that it produced walking motions. It provided a design language for a difficult class of robots: choose virtual constraints, use the robot's own motion as a phase variable, reduce the closed-loop dynamics to a lower-dimensional invariant surface, and analyze stability through the resulting hybrid dynamics. The method kept the essential features of legged locomotion, including underactuation and impact, instead of designing around them.

The work moved deliberately from theory to hardware. RABBIT provided an early experimental platform for underactuated walking. MABEL showed that the ideas could be extended to a compliant robot capable of dynamic walking and running. MARLO moved the agenda toward 3D outdoor walking. Later work on Cassie Blue helped bring these methods onto a widely used research platform, with associated open-source controllers for testing and comparison.

I would not claim that HZD solved legged locomotion, nor that later successes in humanoids, exoskeletons, quadrupeds, optimization, model predictive control, and learning came from one line of work. The more durable contribution is narrower and, I think, more accurate: HZD helped make underactuated dynamic walking analytically respectable, computationally designable, and experimentally credible. It gave researchers a way to connect nonlinear control theory, numerical optimization, and real robot experiments without discarding the hybrid nature of walking.

The work also propagated through people and tools. Students and collaborators extended the framework, built software, carried the ideas into their own laboratories, and connected them to modern legged robots. In parallel, HZD-based algorithms contributed to early work with Wandercraft on self-balancing lower-limb exoskeletons. That translational thread is best stated carefully: HZD did not create commercial exoskeletons by itself, but it supplied control principles and early algorithms for one serious path toward hands-free dynamic walking assistance.

The research legacy I value most is this combination: a mathematical framework, physical demonstrations, open tools, and students and collaborators who carried the ideas beyond the original laboratory.

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

*   [Papers on biped robots](/publications/robotics.html)
*   [Early Videos Pre-YouTube](robot-videos.html)
*   [Michigan Robotics: Dynamic Legged Locomotion YouTube Channel](http://www.youtube.com/user/DynamicLegLocomotion).
*   [Open-source Software for Estimation and Control](https://github.com/UMich-BipedLab)
*   [Wandercraft](https://en.wandercraft.eu/) Early control laws for Wandercraft's exoskeleton were based on HZD. Wandercraft's work is part of a serious effort to make self-balancing, hands-free locomotion available in rehabilitation settings, including for people with paraplegia.
* **Other:** Robots everywhere in our College of Engineering: [Michigan Robotics Rocks!](http://www.youtube.com/watch?v=pMaCC__C0cE&feature=c4-overview-vl&list=PL5CFFA0DE541898F8), This is Michigan Engineering [2012](http://www.youtube.com/watch?v=e-p1QiRgxWo&feature=c4-overview-vl&list=PL5CFFA0DE541898F8), [Michigan Halftime Video](http://www.youtube.com/watch?v=guj0Ddp4bEA&list=PL5CFFA0DE541898F8), Victors for Michigan Campaign video [short](http://www.youtube.com/watch?v=8C_JpoZeUSk) (MABEL is at 0:16) and [long version](http://www.youtube.com/watch?v=_Mcf4UiaYQA) (MABEL is at 2:01), and MABEL goes to the [Field Museum in Chicago.](https://www.youtube.com/watch?v=7qr9zVpqIiw)

<br>

**There was a before-bipeds phase:** I got my start in research as an undergraduate at Oklahoma State University in 1977, when Prof. Robert Mulholland recruited me as a research assistant for his work on modeling the global carbon cycle, a precursor to climate modeling.
R. J. Mulholland and J. W. Grizzle, ["Modeling Perturbations of the Global Carbon Cycle,"](/files/GlobalCarbonCycle1979.pdf) _Reprint,_ Proc. of the International Conference on Cybernetics and Society, pp. 690-694, 1979. And yes, it has always been about fossil fuels. Beginning in 1980 at UT Austin, studying under Prof. Steven Marcus, my primary research area became the theory of nonlinear control systems. The work I did on control methods steeped in differential geometry laid the foundations for my later work in bipedal robotics. While I always maintained a strong interest in this subject and felt a sense of community with that body of researchers, my research activities significantly broadened over time. From 1986 to 2010, I worked with my dear friend and colleague, [Jeffrey Cook](https://www.automotivehalloffame.org/honoree/jeffrey-a-cook/), on various aspects of modeling and control of automotive powertrain systems; we helped turn the automotive area into a respectable academic discipline. From 2007 to 2012, I collaborated with [Prof. Huei Peng](https://scholar.google.com/citations?user=MMgcQiIAAAAJ&hl=en) on Hybrid Electric Vehicles (HEVs). From 1991 to 2001, I applied systems and control techniques to improve the operation of plasma-based microelectronics manufacturing equipment. From 2014 through 2018, I worked with an esteemed group of researchers on correct-by-construction control methods, with the primary application area being Advanced Driver Assist Systems.

*   [Papers on automotive control](automotive.html)
*   [Papers on nonlinear control theory](control.html)
*   [Papers on semiconductor manufacturing](semiconductor.html)
*   [Models coded in MATLAB](matlab.html)
