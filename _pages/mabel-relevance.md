---
permalink: /robot-videos/mabel/relevance
title: "MABEL Relevance"
excerpt: "MABEL the walking robot: relevance"
author_profile: true

---
**Relevance to robots with feet and 3D robots.** It is important to understand the relevance of research on planar robots with unactuated point feet in the larger context of 3D robots with feet.

**Underactuation-101:** In a robot with feet, there are phases of a walking gait where the feet are in rotation with respect to the ground, such as toe roll and heel strike, and hence the robot is underactuated (fewer actuators than degrees of freedom). The prevailing technique of control based on the Zero Moment Point (ZMP) can only handle the flat-footed phase, and hence yields very unnatural gaits; moreover, in practice, large (heavy) feet are used to avoid foot rotation. The study of unactuated point feet leads to the development of a control theory for bipeds that deals directly with underactuation. It is then possible to design feedback controllers for robots with feet that yield natural gaits which include both underactuated, fully-actuated and over actuated phases. This becomes even more critical in 3D robots because feet are typically much less wide than they are long, which means that very little torque can be applied in the frontal plane (i.e., side to side) without causing the foot to roll sideways. It is therefore of practical interest to generate a nominally stable gait that requires no ankle torque in the frontal plane, and then use any available torque to enhance the basin of attraction and/or energy efficiency of the gait.

**Underactuation-201:** Once you begin to attack one aspect of underactuation, you are encouraged to try to analyze other aspects. We are now studying underactuation that arises from compliance. This gives rise to higher-dimensional hybrid zero dynamics, a very interesting subject!

**Generalizations to 3D:** We and our colleagues have designed an exponentially stable walking gait for 3D robots with unactuated point feet. This work draws very heavily on the theory of hybrid zero dynamics that we developed for planar walkers; designing the closed-loop system around invariant manifolds and restriction dynamics made the stability analysis much more tractable. Without the theoretical tools systematically developed for planar robots, the analytical complexities present in the 3D problem would have seemed insurmountable.

**Safety:** As a final note, in a laboratory run by faculty and graduate students, without the benefit of a professional technician, a planar robot is safer than a 3D robot; this is because I and my students can easily remain out of the workspace of the robot without enclosing the robot in a cage.