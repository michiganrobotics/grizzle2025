---
title: "Education | Mathematics and Control"
collection: education
permalink: /education/
author_profile: false
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@600;700;800&family=Libre+Franklin:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  /* --- Theme integration scaffold (not scoped: targets the academicpages template) --- */
  #main:has(.rob-page) { max-width: none; margin: 0; padding: 0; overflow-x: hidden; }
  .page:has(.rob-page) { float: none; width: 100%; margin: 0; padding: 0; }
  .page:has(.rob-page) .page__inner-wrap,
  .page:has(.rob-page) .page__content { margin: 0; padding: 0; width: 100%; max-width: none; }
  .page:has(.rob-page) .page__content h2 { border-bottom: 0; padding-bottom: 0; }
  .page:has(.rob-page) > .page__inner-wrap > header { display: none; }
  .rob-page { width: 100%; max-width: 100%; overflow-x: hidden; }
  /* Sticky course subnav: pins to top once the site masthead scrolls away */
  .rob-page .course-subnav { position: sticky; top: 0; z-index: 30; background: var(--blue); border-bottom: 2px solid var(--maize); }
  .rob-page .course-subnav-inner { max-width: var(--maxw); margin: 0 auto; padding: .5rem 1.4rem; display: flex; align-items: center; justify-content: space-between; gap: .75rem 1.25rem; flex-wrap: wrap; }
  .rob-page .course-subnav-label { font-family: var(--font-display); font-weight: 800; color: var(--maize); font-size: .82rem; letter-spacing: .08em; text-transform: uppercase; }
  .rob-page .course-subnav-links { display: flex; gap: .15rem; flex-wrap: wrap; }
  .rob-page .course-subnav-links a { font-family: var(--font-display); font-weight: 700; font-size: .9rem; color: #fff; text-decoration: none; padding: .35rem .6rem; border-radius: 5px; line-height: 1.2; }
  .rob-page .course-subnav-links a:hover { background: rgba(255, 255, 255, .14); color: var(--maize); }
  .rob-page .course-subnav :focus-visible { outline-color: var(--maize); }
  .rob-page section[id] { scroll-margin-top: 3.5rem; }

  .rob-page { --blue: #00274c;
      --blue-2: #0b3d91;
      --maize: #ffcb05;
      --ink: #17212f;
      --muted: #4d5b68;
      --line: #d8dee8;
      --soft: #f3f6fb;
      --white: #ffffff;
      --maxw: 1180px;
      --font-display: "Archivo", ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif;
      --font-body: "Libre Franklin", ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif; }
  .rob-page * { box-sizing: border-box; }
  .rob-page { scroll-behavior: smooth; }
  .rob-page { margin: 0;
      font-family: var(--font-body);
      color: var(--ink);
      background: #fbfcff;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased; }
  .rob-page img { display: block; max-width: 100%; height: auto; }
  .rob-page a { color: var(--blue-2); overflow-wrap: anywhere; }
  .rob-page :focus-visible { outline: 3px solid var(--blue-2); outline-offset: 2px; border-radius: 4px; }
  .rob-page .hero :focus-visible, .rob-page .band :focus-visible { outline-color: var(--maize); }
  @media (prefers-reduced-motion: reduce) {
    .rob-page { scroll-behavior: auto; }
    .rob-page *, .rob-page *::before, .rob-page *::after { transition-duration: 0.01ms !important; animation-duration: 0.01ms !important; animation-iteration-count: 1 !important; }
  }
  .rob-page p, .rob-page li, .rob-page dd { line-height: 1.62; overflow-wrap: break-word; text-wrap: pretty; }
  .rob-page h1, .rob-page h2, .rob-page h3 { font-family: var(--font-display);
      color: var(--blue);
      line-height: 1.1;
      letter-spacing: 0;
      text-wrap: balance; }
  .rob-page h1 { font-size: clamp(2.4rem, 6vw, 4.85rem); font-weight: 800; margin: 0; max-width: 1040px; }
  .rob-page h2 { font-size: clamp(1.75rem, 3.3vw, 2.65rem); font-weight: 700; margin: 0 0 1rem; }
  .rob-page h3 { font-size: clamp(1.16rem, 2.1vw, 1.55rem); font-weight: 700; margin: 0 0 .55rem; }
  .rob-page .eyebrow, .rob-page .button, .rob-page .hero-fact strong, .rob-page .course-code, .rob-page .deflist-row dt, .rob-page .resource-item a { font-family: var(--font-display); }
  .rob-page .hero { min-height: 76vh;
      display: grid;
      align-items: end;
      color: var(--white);
      background:
        linear-gradient(90deg, rgba(0, 39, 76, .94) 0%, rgba(0, 39, 76, .8) 48%, rgba(0, 39, 76, .24) 100%),
        url("/images/preview/robotics-bldg-web.jpg") center / cover no-repeat; }
  .rob-page .hero-inner { width: 100%;
      max-width: var(--maxw);
      margin: 0 auto;
      padding: min(12vh, 7rem) 1.15rem 3rem; }
  .rob-page .eyebrow { color: var(--maize);
      font-size: .86rem;
      font-weight: 800;
      letter-spacing: .08em;
      text-transform: uppercase;
      margin-bottom: .9rem; }
  .rob-page .hero h1, .rob-page .hero p { color: var(--white); }
  .rob-page .hero h1 a { color: #fff;
      text-decoration-color: var(--maize);
      text-decoration-thickness: 4px;
      text-underline-offset: .12em; }
  .rob-page .hero h1 a:hover { color: var(--maize); }
  .rob-page .lede { max-width: 860px; font-size: clamp(1.12rem, 2.2vw, 1.52rem); margin: 1rem 0 1.35rem; }
  .rob-page .hero-actions { display: flex; gap: .75rem; flex-wrap: wrap; align-items: center; }
  .rob-page .button { display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 2.75rem;
      padding: .68rem 1rem;
      border: 2px solid transparent;
      border-radius: 6px;
      font-weight: 800;
      text-decoration: none;
      line-height: 1.15;
      transition: background-color .18s ease, border-color .18s ease, color .18s ease, transform .18s ease; }
  .rob-page .button:hover { transform: translateY(-1px); }
  .rob-page .button.primary { background: var(--maize); color: var(--blue); }
  .rob-page .button.secondary { background: rgba(255, 255, 255, .1); border-color: rgba(255, 255, 255, .72); color: var(--white); }
  .rob-page .hero-courses { display: grid;
      grid-template-columns: repeat(auto-fit, minmax(min(185px, 100%), 1fr));
      gap: 1rem;
      margin-top: 2.35rem;
      max-width: 1120px; }
  .rob-page .hero-course { display: grid;
      align-content: start;
      gap: .75rem;
      min-height: 15rem;
      padding: clamp(1.2rem, 2.4vw, 1.7rem);
      color: #fff;
      background: rgba(0, 39, 76, .86);
      border: 1px solid rgba(255, 255, 255, .22);
      border-radius: 8px;
      box-shadow: 0 18px 46px rgba(0, 20, 40, .28);
      backdrop-filter: blur(5px); }
  .rob-page .hero-course strong { display: block;
      color: var(--maize);
      font-size: 1rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: .04em; }
  .rob-page .hero-course p { margin: 0;
      font-size: clamp(1.18rem, 2.2vw, 1.55rem);
      line-height: 1.18;
      color: #fff; }
  .rob-page .hero-course-links { display: flex;
      flex-wrap: wrap;
      gap: .45rem .9rem;
      margin-top: auto;
      padding-top: .7rem;
      border-top: 1px solid rgba(255, 255, 255, .18); }
  .rob-page .hero-course-links a { color: #fff;
      font-weight: 800;
      text-decoration-color: var(--maize);
      text-decoration-thickness: 2px;
      text-underline-offset: 3px; }
  .rob-page .section { max-width: var(--maxw); margin: 0 auto; padding: clamp(3rem, 6vw, 5rem) 1.15rem; }
  .rob-page .section.compact { padding-top: clamp(2.25rem, 4vw, 3rem); padding-bottom: clamp(2.25rem, 4vw, 3rem); }
  .rob-page .section-intro { max-width: 820px; font-size: 1.08rem; color: var(--muted); margin: 0 0 1.5rem; }
  .rob-page .band { background: var(--blue); color: #fff; }
  .rob-page .band h2, .rob-page .band h3, .rob-page .band p, .rob-page .band li, .rob-page .band dt, .rob-page .band dd { color: #fff; }
  .rob-page .band .section-intro { color: rgba(255, 255, 255, .82); }
  .rob-page .career-note { max-width: 920px;
      padding-bottom: clamp(1.75rem, 4vw, 2.75rem);
      margin-bottom: clamp(1.75rem, 4vw, 2.75rem);
      border-bottom: 1px solid rgba(255, 255, 255, .28); }
  .rob-page .career-note h2 { font-size: clamp(2rem, 4vw, 3.35rem); }
  .rob-page .split { display: grid;
      grid-template-columns: minmax(0, 1.08fr) minmax(280px, .92fr);
      gap: clamp(1.5rem, 4vw, 2.75rem);
      align-items: start; }
  .rob-page .image-frame { border-radius: 8px; overflow: hidden; box-shadow: 0 18px 42px rgba(0, 39, 76, .14); background: #fff; }
  .rob-page .caption { font-size: .88rem; color: var(--muted); margin: .55rem 0 0; }
  .rob-page .course-list { border-top: 1px solid var(--line); margin-top: 1.75rem; }
  .rob-page .course-row { display: grid;
      grid-template-columns: minmax(8.5rem, .24fr) minmax(0, .96fr) minmax(11rem, .24fr);
      gap: clamp(1rem, 3vw, 2rem);
      padding: clamp(1.25rem, 3vw, 2rem) 0;
      border-bottom: 1px solid var(--line);
      align-items: start; }
  .rob-page .course-code { color: var(--blue-2);
      font-size: .86rem;
      font-weight: 800;
      letter-spacing: .08em;
      text-transform: uppercase; }
  .rob-page .course-row h3 { font-size: clamp(1.38rem, 2.5vw, 1.95rem); margin-bottom: .55rem; }
  .rob-page .course-row p { margin: 0 0 .75rem; color: var(--muted); }
  .rob-page .course-row ul { margin: .75rem 0 0; padding-left: 1.1rem; color: var(--muted); }
  .rob-page .course-links { display: grid; gap: .45rem; align-content: start; }
  .rob-page .course-links a { font-weight: 700; }
  .rob-page .ideas { display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      margin-top: 1.5rem;
      border-top: 1px solid var(--line); }
  .rob-page .idea { padding: clamp(1.25rem, 2.6vw, 2rem) clamp(1rem, 2vw, 1.75rem) clamp(1.25rem, 2.6vw, 2rem) 0; border-bottom: 1px solid var(--line); }
  .rob-page .idea:nth-child(odd) { padding-right: clamp(1.5rem, 3vw, 2.75rem); border-right: 1px solid var(--line); }
  .rob-page .idea:nth-child(even) { padding-left: clamp(1.5rem, 3vw, 2.75rem); }
  .rob-page .idea h3 { margin-bottom: .45rem; }
  .rob-page .idea p { color: var(--muted); margin: 0; }
  .rob-page .deflist { margin: 1.25rem 0 0; border-top: 1px solid var(--line); }
  .rob-page .band .deflist { border-color: rgba(255, 255, 255, .26); }
  .rob-page .deflist-row { display: grid;
      grid-template-columns: minmax(10rem, .28fr) minmax(0, 1fr);
      gap: clamp(.75rem, 2vw, 1.5rem);
      padding: .95rem 0;
      border-bottom: 1px solid var(--line); }
  .rob-page .band .deflist-row { border-color: rgba(255, 255, 255, .26); }
  .rob-page .deflist-row dt { font-weight: 800; color: var(--blue); margin: 0; }
  .rob-page .band .deflist-row dt { color: var(--maize); }
  .rob-page .deflist-row dd { margin: 0; color: var(--muted); }
  .rob-page .band .deflist-row dd { color: rgba(255, 255, 255, .94);
      font-weight: 500; }
  .rob-page .resource-list { border-top: 1px solid var(--line); margin-top: 1.3rem; }
  .rob-page .resource-item { display: grid;
      grid-template-columns: minmax(11rem, .28fr) minmax(0, 1fr) minmax(8rem, .18fr);
      gap: clamp(.8rem, 2vw, 1.5rem);
      align-items: start;
      padding: 1.05rem 0;
      border-bottom: 1px solid var(--line); }
  .rob-page .resource-item h3 { font-size: 1.05rem; margin: 0; }
  .rob-page .resource-item p { margin: 0; color: var(--muted); }
  .rob-page .resource-item a { font-weight: 800; }
  .rob-page .link-note { color: var(--muted); font-size: .92rem; margin-top: 1rem; }
  @media (max-width: 820px) {
    .rob-page .course-subnav { position: static; }
    .rob-page .course-subnav-inner { display: block; padding: .55rem 1rem; }
    .rob-page .course-subnav-label { display: block; margin-bottom: .25rem; }
    .rob-page .course-subnav-links { width: 100%; justify-content: flex-start; }
    .rob-page .course-subnav-links a { font-size: .82rem; padding: .38rem .45rem; }
    .rob-page .hero { min-height: 720px;
        background:
          linear-gradient(180deg, rgba(0, 39, 76, .96) 0%, rgba(0, 39, 76, .84) 58%, rgba(0, 39, 76, .52) 100%),
          url("/images/preview/robotics-bldg-web.jpg") center / cover no-repeat; }
    .rob-page h1 { font-size: 1.75rem; max-width: 22rem; }
    .rob-page .lede { font-size: 1rem; max-width: 22rem; }
    .rob-page .hero-actions { display: grid; grid-template-columns: 1fr; max-width: 22rem; }
    .rob-page .hero-courses { grid-template-columns: 1fr; max-width: 22rem; }
    .rob-page .hero-course { min-height: 0; }
    .rob-page .split, .rob-page .course-row, .rob-page .deflist-row, .rob-page .resource-item { grid-template-columns: 1fr; }
    .rob-page .ideas { grid-template-columns: 1fr; }
    .rob-page .idea:nth-child(odd), .rob-page .idea:nth-child(even) { padding-left: 0; padding-right: 0; border-right: none; }
  }
  /* Eyebrows: maize only on dark backgrounds; readable blue on light sections */
  .rob-page .eyebrow { color: var(--blue-2); }
  .rob-page .hero .eyebrow, .rob-page .band .eyebrow { color: var(--maize); }
</style>

  
  

  <div class="rob-page" id="top" markdown="0">
  <nav class="course-subnav" aria-label="Education sections">
    <div class="course-subnav-inner">
      <span class="course-subnav-label">Education</span>
      <div class="course-subnav-links">
        <a href="#courses">Courses</a>
        <a href="#arc">Teaching arc</a>
        <a href="#bipeds">Bipedal locomotion</a>
        <a href="#control">Earlier teaching</a>
        <a href="#resources">Resources</a>
      </div>
    </div>
  </nav>
    <section class="hero" aria-label="Education hero">
      <div class="hero-inner">
        <p class="eyebrow">Michigan Robotics mathematics pathway</p>
        <h1><a href="/education/rob101">ROB 101</a>, <a href="/education/rob201">ROB 201</a>, and <a href="/education/rob501">ROB 501</a>.</h1>
        <p class="lede">A connected sequence of open course materials for computational linear algebra, calculus for modern engineering, and graduate mathematics for robotics.</p>
        <div class="hero-courses" id="courses" aria-label="ROB mathematics courses">
          <article class="hero-course">
            <strong>ROB 101</strong>
            <p>Computational linear algebra for robotics, data, and AI-scale applications.</p>
            <div class="hero-course-links">
              <a href="/education/rob101">Course page</a>
              <a href="https://github.com/michiganrobotics/rob101">GitHub</a>
            </div>
          </article>
          <article class="hero-course">
            <strong>ROB 201</strong>
            <p>Calculus as modeling, motion, numerical methods, and control.</p>
            <div class="hero-course-links">
              <a href="/education/rob201">Course page</a>
              <a href="https://github.com/michiganrobotics/rob201">GitHub</a>
            </div>
          </article>
          <article class="hero-course">
            <strong>ROB 501</strong>
            <p>Proof, estimation, probability, real analysis, and optimization.</p>
            <div class="hero-course-links">
              <a href="/education/rob501">Course page</a>
              <a href="https://github.com/michiganrobotics/rob501">GitHub</a>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="arc">
        <div class="career-note">
          <p class="eyebrow">Teaching career</p>
          <h2>Teaching the mathematics behind robotics.</h2>
          <p class="section-intro">Bringing an open source mindset to teaching through freely available course notes, textbooks, lectures, and project materials.</p>
        </div>
        <div class="split">
          <div>
            <h2>A career dedicated to outstanding teaching alongside pioneering research.</h2>
            <p class="section-intro">Jessy's teaching persona is rigorous but inviting: grounded in robotics and feedback control, serious about mathematical structure, and animated by helping students move from intuition to formal tools.</p>
          </div>
          <div>
            <dl class="deflist">
              <div class="deflist-row"><dt>Modeling</dt><dd>Connect physical systems to equations, approximations, and simulation.</dd></div>
              <div class="deflist-row"><dt>Computation</dt><dd>Use code and numerical methods to make mathematics operational.</dd></div>
              <div class="deflist-row"><dt>Control</dt><dd>Turn models into feedback laws for robots that move through the world.</dd></div>
              <div class="deflist-row"><dt>Inference</dt><dd>Give students the proof, estimation, probability, and optimization tools needed for robotics research.</dd></div>
            </dl>
          </div>
        </div>
    </section>

    <section class="section" id="bipeds">
      <h2>How to learn modeling and feedback control of bipedal locomotion</h2>
      <p class="section-intro">For students and researchers wanting to learn bipedal locomotion, the materials are best read as a progression: begin with undergraduate bootcamp notes, move into the 2007 monograph, and then continue to later papers and tutorial surveys that extend the method.</p>
      <div class="course-list">
        <article class="course-row">
          <div class="course-code">Start</div>
          <div>
            <h3>Undergraduate bootcamp notes</h3>
            <p><a href="https://wamiogunbi.com/biped-bootcamp">Dr. Wami Ogunbi's Bipedal Bootcamp</a> is the best starting point for undergraduates who want to learn control of bipedal locomotion before moving into the research monograph.</p>
          </div>
          <div class="course-links">
            <a href="https://wamiogunbi.com/biped-bootcamp">Start bootcamp</a>
          </div>
        </article>
        <article class="course-row">
          <div class="course-code">Foundation</div>
          <div>
            <h3>Research monograph</h3>
            <p><a href="https://grizzle.robotics.umich.edu/publications/biped-book"><em>Feedback Control of Dynamic Bipedal Robot Locomotion</em></a>, co-authored with Eric R. Westervelt, Christine Chevallereau, Jun-Ho Choi, and Benjamin Morris, was published by Taylor &amp; Francis in June 2007 and is available for free <a href="https://grizzle.robotics.umich.edu/files/Westervelt_biped_control_book_15_May_2007.pdf">download</a>.</p>
            <p>It treats virtual constraints and hybrid zero dynamics for the creation of asymptotically stable periodic motions in hybrid systems.</p>
          </div>
          <div class="course-links">
            <a href="https://grizzle.robotics.umich.edu/publications/biped-book">Book page</a>
            <a href="https://grizzle.robotics.umich.edu/files/Westervelt_biped_control_book_15_May_2007.pdf">Download PDF</a>
          </div>
        </article>
        <article class="course-row">
          <div class="course-code">Extensions</div>
          <div>
            <h3>Methods developed after the monograph</h3>
            <p>These papers significantly extend virtual constraints and hybrid zero dynamics: <a href="https://arxiv.org/abs/1711.02223">Machine Learning</a>, <a href="https://arxiv.org/abs/2105.08170">Zero Dynamics and Low-order Models</a>, <a href="https://arxiv.org/abs/2109.14862">MPC and Virtual Constraints</a>, <a href="http://journals.sagepub.com/doi/abs/10.1177/0278364917708249">Robust Optimization</a>, and <a href="http://journals.sagepub.com/doi/abs/10.1177/0278364915593400">Bilinear Matrix Inequalities (BMI)</a>.</p>
          </div>
          <div class="course-links">
            <a href="https://arxiv.org/abs/1711.02223">Machine learning</a>
            <a href="https://arxiv.org/abs/2105.08170">Low-order models</a>
            <a href="https://arxiv.org/abs/2109.14862">MPC</a>
            <a href="http://journals.sagepub.com/doi/abs/10.1177/0278364917708249">Robust optimization</a>
            <a href="http://journals.sagepub.com/doi/abs/10.1177/0278364915593400">BMI</a>
          </div>
        </article>
        <article class="course-row">
          <div class="course-code">Tutorials</div>
          <div>
            <h3>Review and survey material</h3>
            <p>For broader orientation, see the <a href="http://ames.caltech.edu/HZD_bookchapter.pdf">2018 HZD Review paper by Ames and Poulakakis</a>, the Springer reference chapter <a href="https://arxiv.org/abs/1706.01127"><em>Humanoid Robotics: A Reference</em></a>, and the <a href="https://www.sciencedirect.com/science/article/pii/S0005109814001654">2015 survey on HZD in <em>Automatica</em></a>.</p>
          </div>
          <div class="course-links">
            <a href="http://ames.caltech.edu/HZD_bookchapter.pdf">HZD review</a>
            <a href="https://arxiv.org/abs/1706.01127">Reference chapter</a>
            <a href="https://www.sciencedirect.com/science/article/pii/S0005109814001654">Automatica survey</a>
          </div>
        </article>
      </div>
    </section>

    <section class="band" id="control">
      <div class="section">
        <h2>Earlier teaching in feedback control and applied mathematics</h2>
        <p class="section-intro">From 1987 to 2020, Jessy taught courses primarily in feedback control and applied mathematics for engineering. At the University of Michigan EECS Department, these included:</p>
        <dl class="deflist">
          <div class="deflist-row"><dt>EECS 216</dt><dd>Signals and Systems</dd></div>
          <div class="deflist-row"><dt>EECS 460</dt><dd>Control Systems Analysis and Design</dd></div>
          <div class="deflist-row"><dt>EECS 560</dt><dd>Linear Systems Theory</dd></div>
          <div class="deflist-row"><dt>EECS 562</dt><dd>Nonlinear Systems and Control</dd></div>
          <div class="deflist-row"><dt>EECS 600</dt><dd>Function Space Methods for Systems Theory</dd></div>
          <div class="deflist-row"><dt>EECS 662</dt><dd>Advanced Nonlinear Control</dd></div>
        </dl>
        <p class="section-intro" style="margin-top: 1.5rem;">Course notes for the EECS courses have been passed on to Professors Necmiye Ozay and Dimitra (Mika) Panagou.</p>
      </div>
    </section>

    <section class="section compact" id="resources">
      <h2>Resources</h2>
      <p class="section-intro">Course pages, repositories, and bipedal locomotion materials collected for students and colleagues.</p>
      <div class="resource-list">
        <div class="resource-item"><h3>ROB 101</h3><p>Computational Linear Algebra.</p><a href="/education/rob101">Course page</a></div>
        <div class="resource-item"><h3>ROB 201</h3><p>Calculus for the Modern Engineer.</p><a href="/education/rob201">Course page</a></div>
        <div class="resource-item"><h3>ROB 501</h3><p>Mathematics for Robotics.</p><a href="/education/rob501">Course page</a></div>
        <div class="resource-item"><h3>Course repositories</h3><p>Open GitHub repositories for ROB 101, ROB 201, and ROB 501.</p><a href="https://github.com/michiganrobotics">Browse GitHub</a></div>
        <div class="resource-item"><h3>Biped Bootcamp</h3><p>Undergraduate-friendly modeling and control lessons.</p><a href="https://wamiogunbi.com/biped-bootcamp">Start bootcamp</a></div>
        <div class="resource-item"><h3>Bipedal locomotion monograph</h3><p>Free PDF of the 2007 Taylor &amp; Francis monograph.</p><a href="https://grizzle.robotics.umich.edu/files/Westervelt_biped_control_book_15_May_2007.pdf">Download PDF</a></div>
        <div class="resource-item"><h3>Advanced extensions</h3><p>Machine learning, low-order models, MPC, robust optimization, and BMI extensions.</p><a href="#bipeds">Use the learning path</a></div>
        <div class="resource-item"><h3>HZD tutorials and surveys</h3><p>Review, reference chapter, and Automatica survey material.</p><a href="#bipeds">Use the learning path</a></div>
      </div>
    </section>
  </div>

  
