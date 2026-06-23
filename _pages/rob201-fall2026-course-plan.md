---
title: "ROB 201 Fall 2026 Course Plan"
collection: education
permalink: /education/rob201-fall2026-course-plan
author_profile: false
share: false
---

<!--
Maintainer note: the master source for this schedule is ROB201_Fall2026_Source.txt in the ROB 201 Fall 2026 Course Administration folder. The mapped TSV, PDF, Google Doc, and this interactive page are downstream artifacts. Edit the master source first, then regenerate/update derived outputs.
-->
<style>
  #main:has(.rob201-plan-page) { max-width: none; margin: 0; padding: 0; overflow-x: hidden; }
  .page:has(.rob201-plan-page) { float: none; width: 100%; margin: 0; padding: 0; }
  .page:has(.rob201-plan-page) .page__inner-wrap,
  .page:has(.rob201-plan-page) .page__content { margin: 0; padding: 0; width: 100%; max-width: none; }
  .page:has(.rob201-plan-page) > .page__inner-wrap > header { display: none; }
  .rob201-plan-page {
    --blue: #00274c;
    --blue-2: #315f8f;
    --maize: #ffcb05;
    --ink: #182533;
    --muted: #566573;
    --line: #d7dee8;
    --soft-blue: #f1f6fb;
    --soft-maize: #fff8dc;
    --white: #ffffff;
    font-family: Arial, Helvetica, sans-serif;
    color: var(--ink);
    background: #fbfcff;
    line-height: 1.45;
  }
  .rob201-plan-page * { box-sizing: border-box; }
  .rob201-plan-page a { color: #174f8a; }
  .rob201-plan-page .hero {
    background: var(--blue);
    color: var(--white);
    border-left: 12px solid var(--maize);
  }
  .rob201-plan-page .inner { max-width: 1120px; margin: 0 auto; padding: 22px 22px; }
  .rob201-plan-page h1,
  .rob201-plan-page h2,
  .rob201-plan-page h3 { color: var(--blue); letter-spacing: 0; }
  .rob201-plan-page .hero h1 { color: var(--white); margin: 0 0 8px; font-size: 2rem; }
  .rob201-plan-page .hero p { margin: 0; color: #f7f2df; font-size: 1.04rem; max-width: 900px; }
  .rob201-plan-page .toolbar-wrap { background: var(--white); border-bottom: 1px solid var(--line); position: sticky; top: 0; z-index: 5; }
  .rob201-plan-page .toolbar { display: flex; align-items: center; justify-content: space-between; gap: 14px; flex-wrap: wrap; }
  .rob201-plan-page .button-row { display: flex; align-items: center; gap: 8px; flex-wrap: wrap; }
  .rob201-plan-page button,
  .rob201-plan-page .link-button {
    border: 1px solid #b8c5d4;
    background: #ffffff;
    color: var(--blue);
    min-height: 38px;
    padding: 7px 12px;
    border-radius: 6px;
    font-weight: 700;
    cursor: pointer;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 6px;
    line-height: 1.2;
  }
  .rob201-plan-page button:hover,
  .rob201-plan-page .link-button:hover { border-color: var(--blue); background: var(--soft-blue); text-decoration: none; }
  .rob201-plan-page button.primary { background: var(--maize); border-color: #d4aa00; color: var(--blue); }
  .rob201-plan-page button:disabled { opacity: .45; cursor: not-allowed; }
  .rob201-plan-page .week-select { min-height: 38px; border: 1px solid #b8c5d4; border-radius: 6px; padding: 6px 10px; color: var(--blue); background: #fff; font-weight: 700; max-width: 100%; }
  .rob201-plan-page .status { font-weight: 700; color: var(--blue); }
  .rob201-plan-page .summary-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(210px, 1fr)); gap: 12px; margin: 18px 0; }
  .rob201-plan-page .summary-card { border: 1px solid var(--line); border-top: 5px solid var(--maize); background: var(--soft-maize); padding: 12px; border-radius: 4px; }
  .rob201-plan-page .summary-card:nth-child(even) { border-top-color: var(--blue-2); background: var(--soft-blue); }
  .rob201-plan-page .summary-card h2 { font-size: 1.05rem; margin: 0 0 6px; }
  .rob201-plan-page .summary-card p { margin: 0; color: var(--muted); }
  .rob201-plan-page .viewer { display: grid; grid-template-columns: minmax(0, 1fr); gap: 14px; }
  .rob201-plan-page .week-card { background: #fff; border: 1px solid var(--line); border-top: 8px solid var(--blue); border-radius: 5px; box-shadow: 0 8px 22px rgba(0, 39, 76, .08); }
  .rob201-plan-page .week-head { padding: 16px; border-bottom: 1px solid var(--line); display: flex; justify-content: space-between; align-items: flex-start; gap: 16px; flex-wrap: wrap; }
  .rob201-plan-page .week-head h2 { margin: 0 0 4px; font-size: 1.45rem; }
  .rob201-plan-page .date-range { color: var(--muted); font-weight: 700; }
  .rob201-plan-page .tag { display: inline-flex; align-items: center; border: 1px solid #c9d4e1; background: var(--soft-blue); color: var(--blue); border-radius: 999px; padding: 4px 9px; font-size: .88rem; font-weight: 700; }
  .rob201-plan-page .week-body { padding: 16px; display: grid; gap: 14px; }
  .rob201-plan-page .two-col { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 12px; }
  .rob201-plan-page .panel { border: 1px solid var(--line); background: #fff; border-radius: 4px; padding: 12px; }
  .rob201-plan-page .panel h3 { margin: 0 0 8px; font-size: 1.02rem; }
  .rob201-plan-page .lecture-line { display: grid; grid-template-columns: 90px minmax(0, 1fr); gap: 10px; padding: 8px 0; border-top: 1px solid #edf1f5; }
  .rob201-plan-page .lecture-line:first-of-type { border-top: 0; padding-top: 0; }
  .rob201-plan-page .day { font-weight: 800; color: var(--blue); }
  .rob201-plan-page .assignments { margin: 0; padding-left: 20px; }
  .rob201-plan-page .assignments li { margin: 4px 0; }
  .rob201-plan-page .muted { color: var(--muted); }
  .rob201-plan-page .all-weeks { margin-top: 22px; }
  .rob201-plan-page details { border: 1px solid var(--line); border-radius: 4px; background: #fff; margin: 8px 0; }
  .rob201-plan-page summary { cursor: pointer; padding: 10px 12px; font-weight: 800; color: var(--blue); }
  .rob201-plan-page .mini-week { padding: 0 12px 12px; color: var(--muted); }
  .rob201-plan-page .notice { border-left: 5px solid var(--maize); background: var(--soft-maize); padding: 10px 12px; margin: 16px 0; }
  @media (max-width: 640px) {
    .rob201-plan-page .inner { padding: 16px 14px; }
    .rob201-plan-page .hero h1 { font-size: 1.55rem; }
    .rob201-plan-page .toolbar { align-items: stretch; }
    .rob201-plan-page .button-row, .rob201-plan-page button, .rob201-plan-page .link-button, .rob201-plan-page .week-select { width: 100%; justify-content: center; }
    .rob201-plan-page .lecture-line { grid-template-columns: 1fr; gap: 2px; }
  }
</style>

<div class="rob201-plan-page">
  <section class="hero">
    <div class="inner">
      <h1>ROB 201 Fall 2026 Course Plan</h1>
      <p>A week-by-week map for lectures, homework, optional PrairieLearn practice tests, PrairieLearn tests, projects, and the final exam. Canvas and Gradescope remain authoritative for submission details and deadlines.</p>
    </div>
  </section>

  <div class="toolbar-wrap">
    <div class="inner toolbar" aria-label="Course plan navigation">
      <div class="button-row">
        <button id="prev-week" type="button" aria-label="Previous week">&#8592; Previous</button>
        <button id="this-week" type="button" class="primary">This Week</button>
        <button id="next-week" type="button" aria-label="Next week">Next &#8594;</button>
      </div>
      <select id="week-select" class="week-select" aria-label="Choose week"></select>
      <div id="week-status" class="status" aria-live="polite"></div>
    </div>
  </div>

  <main class="inner">
    <div class="summary-grid" aria-label="Key resources">
      <div class="summary-card">
        <h2>Official PDF</h2>
        <p><a href="https://umich.instructure.com/courses/865276/files/folder/Syllabus?preview=46527131">Printable course plan PDF</a></p>
      </div>
      <div class="summary-card">
        <h2>Canvas</h2>
        <p><a href="https://umich.instructure.com/courses/865276/assignments/syllabus">Course syllabus page</a></p>
      </div>
      <div class="summary-card">
        <h2>Written HW</h2>
        <p><a href="https://umich.instructure.com/courses/865276/files/folder/HW%20Written">Written HW folder</a></p>
      </div>
      <div class="summary-card">
        <h2>Gradescope</h2>
        <p><a href="https://www.gradescope.com/courses/1324719">ROB 201 Gradescope</a></p>
      </div>
    </div>

    <div class="notice">
      <strong>Source of truth:</strong> this interactive page is a student-facing view generated from the ROB 201 Fall 2026 master schedule source. Canvas assignment pages and Gradescope remain authoritative for submission details and deadlines. Use <strong>This Week</strong> to jump to the current part of the term; before the term starts it opens the beginning, and after the term ends it opens the ending.
    </div>

    <section id="week-view" class="viewer" aria-label="Selected week"></section>

    <section class="all-weeks" aria-label="All weeks">
      <h2>Full Schedule</h2>
      <div id="all-weeks"></div>
    </section>
  </main>
</div>

<script>
(function () {
  const weeks = [
    { week: "Week 1", monday: "2026-08-31", lectures: "L01, L02", tuesday: "L01 Start Course Org and C01 Pre-Calculus", thursday: "L02 End C01 Pre-Calculus and Start C02 Calculus Foundations", content: "L01: Course organization; start Chapter 01 Pre-Calculus; L02: Finish Chapter 01 Pre-Calculus; start Chapter 02 Calculus Foundations", assignments: "HW01 posted Friday 09/04", notes: "Chap 01 through 02.5" },
    { week: "Week 2", monday: "2026-09-07", lectures: "L03, L04", tuesday: "L03 End C02 Calculus Foundations", thursday: "L04 Start C03 Definite Integration", content: "L03: Finish Chapter 02 Calculus Foundations; L04: Start Chapter 03 Definite Integration", assignments: "HW01 due Friday midnight HW02 posted Friday 09/11 TestPractice01 available M-F 2026-09-07 to 2026-09-11", notes: "Chap 02.6 through 03.1.1 OPTIONAL, zero points, PrairieLearn practice" },
    { week: "Week 3", monday: "2026-09-14", lectures: "L05, L06", tuesday: "L05 (Continue)", thursday: "L06 End C03 Definite Integration Start C04 Prop of Functions", content: "L05: Continue Chapter 03 Definite Integration; L06: Finish Chapter 03 Definite Integration; start Chapter 04 Properties of Functions", assignments: "HW02 due Friday midnight HW03 posted Friday 09/18 Post Project 1 Friday TestPractice02 available M-F 2026-09-14 to 2026-09-18 Test 1 open M-F 2026-09-14 to 2026-09-18", notes: "Chap 03.1.2 through 03.3.4 Project 1: Chap 1 to 3 OPTIONAL, zero points, PrairieLearn practice N. Campus Testing Center" },
    { week: "Week 4", monday: "2026-09-21", lectures: "L07, L08", tuesday: "L07 (Continue)", thursday: "L08 END C04", content: "L07: Continue Chapter 04 Properties of Functions; L08: End Chapter 04 Properties of Functions", assignments: "HW03 due Friday midnight HW04 posted Friday 09/25 Test 2 open M-F 2026-09-21 to 2026-09-25", notes: "Chap 03.4 through 05.4 N. Campus Testing Center" },
    { week: "Week 5", monday: "2026-09-28", lectures: "L09, L10", tuesday: "L09 Start C05 Differentiation", thursday: "L10 (Continue)", content: "L09: Start Chapter 05 Differentiation; L10: Continue Chapter 05 Differentiation", assignments: "Project 1 due Friday midnight", notes: "" },
    { week: "Week 6", monday: "2026-10-05", lectures: "L11, L12", tuesday: "L11 Continue C05 Differentiation, get close to finishing", thursday: "L12 End Differentiation and Start C06 Eng App. Derivatives", content: "L11: Continue Chapter 05 Differentiation; get close to finishing; L12: End differentiation; start Chapter 06 Engineering Applications of Derivatives", assignments: "HW04 due Friday midnight HW05 posted Friday 10/09 TestPractice03 available M-F 2026-10-05 to 2026-10-09", notes: "Chap. 05.5 to 6.1, maybe 6.2 OPTIONAL, zero points, PrairieLearn practice" },
    { week: "Week 7", monday: "2026-10-12", lectures: "L13, L14", tuesday: "L13 (Continue)", thursday: "L14 (Continue)", content: "L13: Continue Chapter 06 Engineering Applications of Derivatives; L14: Continue Chapter 06 Engineering Applications of Derivatives", assignments: "HW05 due Friday midnight HW06 posted Friday 10/16 Test 3 open M-F 2026-10-12 to 2026-10-16", notes: "Chap 6.3 to 6.4 N. Campus Testing Center" },
    { week: "Week 8", monday: "2026-10-19", lectures: "L15", tuesday: "Fall Break / No Class", thursday: "L15 Finish C06 Eng App. Derivatives and Start C07 Antiderivatives", content: "L15: Finish Chapter 06 Engineering Applications of Derivatives; start Chapter 07 Antiderivatives", assignments: "Post Project 2 Friday", notes: "Project 2: Chap 4 to 6.3" },
    { week: "Week 9", monday: "2026-10-26", lectures: "L16, L17", tuesday: "L16 (Continue)", thursday: "L17 Finish C07 Antiderivatives and Start C08 Improper Integrals", content: "L16: Continue Chapter 07 Antiderivatives; L17: Finish Chapter 07 Antiderivatives; start Chapter 08 Improper Integrals", assignments: "HW06 due Friday midnight HW07 posted Friday 10/30 TestPractice04 available M-F 2026-10-26 to 2026-10-30", notes: "Chap 6.5 to 7.5 OPTIONAL, zero points, PrairieLearn practice" },
    { week: "Week 10", monday: "2026-11-02", lectures: "L18, L19", tuesday: "L18 Finish C08 Improper Integrals and Start C09 ODES", thursday: "L19 (Continue)", content: "L18: Finish Chapter 08 Improper Integrals; start Chapter 09 ODEs; L19: Continue Chapter 09 ODEs", assignments: "HW07 due Friday midnight HW08 posted Friday 11/06 Test 4 open M-F 2026-11-02 to 2026-11-06", notes: "Chap. 8.1 to 10.4 N. Campus Testing Center" },
    { week: "Week 11", monday: "2026-11-09", lectures: "L20, L21", tuesday: "L20 Finish C09 ODEs", thursday: "L21 Start C10 Laplace Transforms", content: "L20: Finish Chapter 09 ODEs; L21: Start Chapter 10 Laplace Transforms", assignments: "Project 2 due Sunday midnight", notes: "" },
    { week: "Week 12", monday: "2026-11-16", lectures: "L22, L23", tuesday: "L22 (Continue)", thursday: "L23 (Continue)", content: "L22: Continue Chapter 10 Laplace Transforms; L23: Continue Chapter 10 after Thanksgiving", assignments: "Post Project 3 Friday", notes: "Project 3: Chap 6.4 to 10" },
    { week: "Week 13", monday: "2026-11-23", lectures: "L24", tuesday: "L24 (Continue)", thursday: "Thanksgiving Break / No Class", content: "L24: Continue Chapter 10 Laplace Transforms", assignments: "TestPractice05 available M-F 2026-11-23 to 2026-11-27", notes: "OPTIONAL, zero points, PrairieLearn practice" },
    { week: "Week 14", monday: "2026-11-30", lectures: "L25, L26", tuesday: "L25 Finish C10 Laplace Transforms and Feedback Control", thursday: "L26 In Class Quiz, no Points", content: "L25: Finish Chapter 10 Laplace Transforms and Feedback Control; L26: In-class quiz / no points", assignments: "HW08 due Friday midnight Test 5 open M-F 2026-11-30 to 2026-12-04", notes: "N. Campus Testing Center" },
    { week: "Week 15", monday: "2026-12-07", lectures: "L27, L28", tuesday: "L27 Special Topics / Project Help", thursday: "L28 Practice Final Exam Review", content: "L27: Special topics, project help, or make-up work; L28: Practice final exam and final exam review", assignments: "Project 3 due Friday midnight", notes: "" },
    { week: "Week 16", monday: "2026-12-14", lectures: "", tuesday: "", thursday: "", content: "", assignments: "Final exam Tuesday, December 15, 4:00 PM - 6:00 PM", notes: "" }
  ];

  const assessments = [
    { type: "Homework", item: "HW01", open: "2026-09-04", close: "2026-09-11", content: "Chap 01 through 02.5" },
    { type: "Homework", item: "HW02", open: "2026-09-11", close: "2026-09-18", content: "Chap 02.6 through 03.1.1" },
    { type: "Homework", item: "HW03", open: "2026-09-18", close: "2026-09-25", content: "Chap 03.1.2 through 03.3.4" },
    { type: "Homework", item: "HW04", open: "2026-09-25", close: "2026-10-09", content: "Chap 03.4 through 05.4" },
    { type: "Homework", item: "HW05", open: "2026-10-09", close: "2026-10-16", content: "Chap. 05.5 to 6.1, maybe 6.2" },
    { type: "Homework", item: "HW06", open: "2026-10-16", close: "2026-10-30", content: "Chap 6.3 to 6.4" },
    { type: "Homework", item: "HW07", open: "2026-10-30", close: "2026-11-06", content: "Chap 6.5 to 7.5" },
    { type: "Homework", item: "HW08", open: "2026-11-06", close: "2026-12-04", content: "Chap. 8.1 to 10.4" },
    { type: "Project", item: "Project 1", open: "2026-09-18", close: "2026-10-02", content: "Chap 1 to 3" },
    { type: "Project", item: "Project 2", open: "2026-10-23", close: "2026-11-15", content: "Chap 4 to 6.3" },
    { type: "Project", item: "Project 3", open: "2026-11-20", close: "2026-12-11", content: "Chap 6.4 to 10" },
    { type: "Practice Test", item: "TestPractice01", open: "2026-09-07", close: "2026-09-11", content: "OPTIONAL, zero points, PrairieLearn practice" },
    { type: "Practice Test", item: "TestPractice02", open: "2026-09-14", close: "2026-09-18", content: "OPTIONAL, zero points, PrairieLearn practice" },
    { type: "Practice Test", item: "TestPractice03", open: "2026-10-05", close: "2026-10-09", content: "OPTIONAL, zero points, PrairieLearn practice" },
    { type: "Practice Test", item: "TestPractice04", open: "2026-10-26", close: "2026-10-30", content: "OPTIONAL, zero points, PrairieLearn practice" },
    { type: "Practice Test", item: "TestPractice05", open: "2026-11-23", close: "2026-11-27", content: "OPTIONAL, zero points, PrairieLearn practice" },
    { type: "Test", item: "Test 1", open: "2026-09-14", close: "2026-09-18", content: "N. Campus Testing Center" },
    { type: "Test", item: "Test 2", open: "2026-09-21", close: "2026-09-25", content: "N. Campus Testing Center" },
    { type: "Test", item: "Test 3", open: "2026-10-12", close: "2026-10-16", content: "N. Campus Testing Center" },
    { type: "Test", item: "Test 4", open: "2026-11-02", close: "2026-11-06", content: "N. Campus Testing Center" },
    { type: "Test", item: "Test 5", open: "2026-11-30", close: "2026-12-04", content: "N. Campus Testing Center" }
  ];

  const msDay = 24 * 60 * 60 * 1000;
  const view = document.getElementById("week-view");
  const allWeeks = document.getElementById("all-weeks");
  const select = document.getElementById("week-select");
  const status = document.getElementById("week-status");
  const prev = document.getElementById("prev-week");
  const next = document.getElementById("next-week");
  const todayBtn = document.getElementById("this-week");
  let currentIndex = 0;

  function parseDate(iso) {
    const parts = iso.split("-").map(Number);
    return new Date(parts[0], parts[1] - 1, parts[2]);
  }
  function endDate(week) {
    return new Date(parseDate(week.monday).getTime() + 6 * msDay);
  }
  function formatDate(date) {
    return date.toLocaleDateString("en-US", { month: "short", day: "numeric" });
  }
  function rangeLabel(week) {
    return `${formatDate(parseDate(week.monday))} - ${formatDate(endDate(week))}`;
  }
  function escapeHtml(text) {
    return String(text || "").replace(/[&<>'"]/g, ch => ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", "'": "&#39;", '"': "&quot;" }[ch]));
  }
  function splitAssignments(text) {
    if (!text) return [];
    return text
      .replace(/ (HW\d\d )/g, "|$1")
      .replace(/ (Post Project \d )/g, "|$1")
      .replace(/ (Project \d due )/g, "|$1")
      .replace(/ (TestPractice\d\d available )/g, "|$1")
      .replace(/ (Test \d open )/g, "|$1")
      .replace(/ (Final exam )/g, "|$1")
      .split("|")
      .map(s => s.trim())
      .filter(Boolean);
  }
  function assessmentItemsForWeek(week) {
    const start = parseDate(week.monday);
    const end = endDate(week);
    return assessments.filter(item => {
      const open = parseDate(item.open);
      const close = parseDate(item.close);
      return (open >= start && open <= end) || (close >= start && close <= end);
    });
  }
  function findTodayIndex(now) {
    const today = new Date(now.getFullYear(), now.getMonth(), now.getDate());
    const first = parseDate(weeks[0].monday);
    const last = endDate(weeks[weeks.length - 1]);
    if (today < first) return 0;
    if (today > last) return weeks.length - 1;
    for (let i = 0; i < weeks.length; i++) {
      if (today >= parseDate(weeks[i].monday) && today <= endDate(weeks[i])) return i;
    }
    for (let i = 0; i < weeks.length; i++) {
      if (today < parseDate(weeks[i].monday)) return i;
    }
    return weeks.length - 1;
  }
  function renderWeek(index) {
    currentIndex = Math.max(0, Math.min(index, weeks.length - 1));
    const week = weeks[currentIndex];
    const bullets = splitAssignments(week.assignments);
    const assessmentRows = assessmentItemsForWeek(week);
    view.innerHTML = `
      <article class="week-card">
        <div class="week-head">
          <div>
            <h2>${escapeHtml(week.week)}</h2>
            <div class="date-range">${rangeLabel(week)}</div>
          </div>
          <span class="tag">${escapeHtml(week.lectures || "Exam week")}</span>
        </div>
        <div class="week-body">
          <div class="two-col">
            <section class="panel">
              <h3>Lecture Meetings</h3>
              <div class="lecture-line"><div class="day">Tuesday</div><div>${escapeHtml(week.tuesday || "No regular class meeting")}</div></div>
              <div class="lecture-line"><div class="day">Thursday</div><div>${escapeHtml(week.thursday || "No regular class meeting")}</div></div>
            </section>
            <section class="panel">
              <h3>Assignments and Tests</h3>
              ${bullets.length ? `<ul class="assignments">${bullets.map(item => `<li>${escapeHtml(item)}</li>`).join("")}</ul>` : `<p class="muted">No major assignment item listed for this week.</p>`}
            </section>
          </div>
          <section class="panel">
            <h3>Content</h3>
            <p>${escapeHtml(week.content || "Final exam period.")}</p>
            ${week.notes ? `<p class="muted"><strong>Notes:</strong> ${escapeHtml(week.notes)}</p>` : ""}
          </section>
          ${assessmentRows.length ? `<section class="panel"><h3>Assessment Windows Touching This Week</h3><ul class="assignments">${assessmentRows.map(item => `<li><strong>${escapeHtml(item.item)}</strong> (${escapeHtml(item.type)}): ${formatDate(parseDate(item.open))} to ${formatDate(parseDate(item.close))}. ${escapeHtml(item.content)}</li>`).join("")}</ul></section>` : ""}
        </div>
      </article>`;
    select.value = String(currentIndex);
    status.textContent = `${week.week} of ${weeks.length}`;
    prev.disabled = currentIndex === 0;
    next.disabled = currentIndex === weeks.length - 1;
  }
  function renderAllWeeks() {
    allWeeks.innerHTML = weeks.map((week, index) => `
      <details>
        <summary>${escapeHtml(week.week)}: ${rangeLabel(week)}${week.lectures ? ` (${escapeHtml(week.lectures)})` : ""}</summary>
        <div class="mini-week">
          <p><strong>Tuesday:</strong> ${escapeHtml(week.tuesday || "No regular class meeting")}</p>
          <p><strong>Thursday:</strong> ${escapeHtml(week.thursday || "No regular class meeting")}</p>
          <p><strong>Assignments:</strong> ${escapeHtml(week.assignments || "None listed")}</p>
          <p><button type="button" data-week-jump="${index}">Open ${escapeHtml(week.week)}</button></p>
        </div>
      </details>`).join("");
  }
  weeks.forEach((week, index) => {
    const option = document.createElement("option");
    option.value = String(index);
    option.textContent = `${week.week}: ${rangeLabel(week)}`;
    select.appendChild(option);
  });
  select.addEventListener("change", () => renderWeek(Number(select.value)));
  prev.addEventListener("click", () => renderWeek(currentIndex - 1));
  next.addEventListener("click", () => renderWeek(currentIndex + 1));
  todayBtn.addEventListener("click", () => renderWeek(findTodayIndex(new Date())));
  allWeeks.addEventListener("click", event => {
    const target = event.target.closest("button[data-week-jump]");
    if (!target) return;
    renderWeek(Number(target.getAttribute("data-week-jump")));
    view.scrollIntoView({ behavior: "smooth", block: "start" });
  });
  renderAllWeeks();
  renderWeek(findTodayIndex(new Date()));
})();
</script>

