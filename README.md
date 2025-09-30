<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Study Timetable — 01 Oct 2025 to 11 Oct 2025</title>
<style>
  :root{
    --bg:#fff8f2;
    --card:#ffffff;
    --accent1:#ffb4a2;
    --accent2:#ffd6a5;
    --accent3:#caffbf;
    --accent4:#9bf6ff;
    --accent5:#bdb2ff;
    --text:#222;
    --muted:#666;
  }
  html,body{font-family: "Segoe UI", Roboto, Arial; background:var(--bg); color:var(--text); margin:0; padding:20px;}
  .page{max-width:1100px; margin:0 auto;}
  header{display:flex; align-items:center; gap:16px; margin-bottom:18px;}
  .logo{
    width:86px; height:86px; border-radius:12px;
    background:linear-gradient(135deg,var(--accent1),var(--accent5));
    display:flex; align-items:center; justify-content:center;
    box-shadow:0 6px 18px rgba(0,0,0,0.08);
    color:#3b2f2f; font-weight:700; font-size:18px;
  }
  header h1{margin:0; font-size:20px; letter-spacing:0.6px;}
  header p{margin:0; color:var(--muted); font-size:13px;}
  table{width:100%; border-collapse:collapse; table-layout:fixed; background:var(--card); box-shadow:0 6px 24px rgba(0,0,0,0.06); border-radius:10px; overflow:hidden;}
  thead th{background:linear-gradient(90deg, var(--accent2), var(--accent4)); padding:12px 10px; font-size:14px; text-align:left; color:#2b2b2b;}
  thead th.small{width:12%;}
  thead th.medium{width:18%;}
  thead th.large{width:36%;}
  tbody tr{border-bottom:1px solid rgba(0,0,0,0.04);}
  tbody tr:nth-child(odd){background:linear-gradient(90deg, rgba(255,255,255,0.6), rgba(255,255,255,0.4));}
  td{padding:12px; vertical-align:top; font-size:13px;}
  .slot{display:flex; flex-direction:column; gap:6px;}
  .time{font-weight:700; font-size:12px; color:var(--muted);}
  .subject-badge{display:inline-block; padding:6px 8px; border-radius:8px; font-weight:600; font-size:13px; color:#0b0b0b;}
  /* subject colors */
  .s-cse1500{background:linear-gradient(90deg,#ffd7d2,#ffb4a2);}
  .s-cse2257{background:linear-gradient(90deg,#ffdca8,#ffd6a5);}
  .s-cse2251{background:linear-gradient(90deg,#d5fddc,#caffbf);}
  .s-cse2253{background:linear-gradient(90deg,#bff6ff,#9bf6ff);}
  .s-mat2501{background:linear-gradient(90deg,#d7d0ff,#bdb2ff);}
  .s-cse2258{background:linear-gradient(90deg,#f0c8ff,#f7b7ff);}
  .exam{background:#fff3b0; padding:8px; border-radius:8px; font-weight:700; display:inline-block;}
  .note{font-size:12px; color:var(--muted);}
  .legend{display:flex; gap:10px; flex-wrap:wrap; margin:12px 0 18px;}
  .legend .item{display:flex; gap:8px; align-items:center; font-size:13px;}
  .badge-mini{width:18px; height:18px; border-radius:5px; display:inline-block;}
  footer{margin-top:16px; color:var(--muted); font-size:13px; text-align:right;}

  /* print friendly */
  @media print{
    body{padding:6mm; background:#fff;}
    header p, footer{display:none;}
    table{box-shadow:none;}
    thead th{background:#f2f2f2 !important;}
    a{color:inherit;}
  }

  /* responsive */
  @media(max-width:800px){
    header{flex-direction:column; align-items:flex-start; gap:6px;}
    .logo{width:66px;height:66px;font-size:16px;}
    thead th{font-size:12px;}
    td{font-size:12px; padding:10px;}
  }
</style>
</head>
<body>
<div class="page">
  <header>
    <div class="logo">STUDY</div>
    <div>
      <h1>Study Timetable — 01 Oct 2025 → 11 Oct 2025</h1>
      <p>Balanced plan — 3–5 subjects daily • Times are study slot suggestions. Exam times shown on exam days.</p>
    </div>
  </header>

  <div class="legend">
    <div class="item"><span class="badge-mini" style="background:linear-gradient(90deg,#ffd7d2,#ffb4a2)"></span> CSE1500</div>
    <div class="item"><span class="badge-mini" style="background:linear-gradient(90deg,#ffdca8,#ffd6a5)"></span> CSE2257</div>
    <div class="item"><span class="badge-mini" style="background:linear-gradient(90deg,#d5fddc,#caffbf)"></span> CSE2251</div>
    <div class="item"><span class="badge-mini" style="background:linear-gradient(90deg,#bff6ff,#9bf6ff)"></span> CSE2253</div>
    <div class="item"><span class="badge-mini" style="background:linear-gradient(90deg,#d7d0ff,#bdb2ff)"></span> MAT2501</div>
    <div class="item"><span class="badge-mini" style="background:linear-gradient(90deg,#f0c8ff,#f7b7ff)"></span> CSE2258</div>
  </div>

  <table role="table" aria-label="Study timetable">
    <thead>
      <tr>
        <th class="small">Date</th>
        <th class="small">Day</th>
        <th class="medium">Morning (08:00 - 11:00)</th>
        <th class="medium">Afternoon (13:00 - 16:00)</th>
        <th class="medium">Evening (17:00 - 19:00)</th>
        <th class="medium">Night (20:00 - 21:00)</th>
        <th class="large">Exam / Notes</th>
      </tr>
    </thead>
    <tbody>
      <!-- 01-10 -->
      <tr>
        <td>01-10-2025</td>
        <td>Wednesday</td>
        <td>
          <div class="slot">
            <div class="time">08:00–11:00</div>
            <div class="subject-badge s-cse1500">CSE1500 — Python (Core concepts & practice)</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">13:00–16:00</div>
            <div class="subject-badge s-cse2257">CSE2257 — Comp Org (Architecture + practice problems)</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">17:00–19:00</div>
            <div class="subject-badge s-cse2251">CSE2251 — DCN (Protocols & diagrams)</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">20:00–21:00</div>
            <div class="subject-badge s-cse2253">CSE2253 — Data Structures (quick problem set)</div>
          </div>
        </td>
        <td class="note">Goal: cover one theory topic + 1 practice problem per subject.</td>
      </tr>

      <!-- 02-10 -->
      <tr>
        <td>02-10-2025</td>
        <td>Thursday</td>
        <td>
          <div class="slot">
            <div class="time">08:00–11:00</div>
            <div class="subject-badge s-cse2257">CSE2257 — Comp Org (timing + important diagrams)</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">13:00–16:00</div>
            <div class="subject-badge s-mat2501">MAT2501 — Integral Transforms & PDE</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">17:00–19:00</div>
            <div class="subject-badge s-cse2258">CSE2258 — Web Technologies (short labs / server basics)</div>
          </div>
        </td>
        <td>
          <div class="slot"><div class="time">20:00–21:00</div><div class="note">Light recap: flashcards</div></div>
        </td>
        <td class="note">Aim: strengthen Comp Org and PDE fundamentals.</td>
      </tr>

      <!-- 03-10 -->
      <tr>
        <td>03-10-2025</td>
        <td>Friday</td>
        <td><div class="slot"><div class="time">08:00–11:00</div><div class="subject-badge s-cse1500">CSE1500 — Python (coding drills)</div></div></td>
        <td><div class="slot"><div class="time">13:00–16:00</div><div class="subject-badge s-cse2251">CSE2251 — DCN (topology & examples)</div></div></td>
        <td><div class="slot"><div class="time">17:00–19:00</div><div class="subject-badge s-cse2253">CSE2253 — Data Structures (trees & graphs)</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="subject-badge s-cse2258">CSE2258 — Web Tech (quick mini-project)</div></div></td>
        <td class="note">Mix of coding + theory to maintain momentum.</td>
      </tr>

      <!-- 04-10 -->
      <tr>
        <td>04-10-2025</td>
        <td>Saturday</td>
        <td><div class="slot"><div class="time">08:00–11:00</div><div class="subject-badge s-mat2501">MAT2501 — PDE practice</div></div></td>
        <td><div class="slot"><div class="time">13:00–16:00</div><div class="subject-badge s-cse2257">CSE2257 — Revise tricky topics</div></div></td>
        <td><div class="slot"><div class="time">17:00–19:00</div><div class="subject-badge s-cse2253">CSE2253 — Data Structures (implementation)</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="note">Flashcard revision & quick past-questions</div></div></td>
        <td class="note">Focus on problem areas identified earlier in the week.</td>
      </tr>

      <!-- 05-10 -->
      <tr>
        <td>05-10-2025</td>
        <td>Sunday</td>
        <td><div class="slot"><div class="time">08:00–11:00</div><div class="subject-badge s-cse2251">CSE2251 — DCN (assignments + diagrams)</div></div></td>
        <td><div class="slot"><div class="time">13:00–16:00</div><div class="subject-badge s-cse1500">CSE1500 — Python (mock test)</div></div></td>
        <td><div class="slot"><div class="time">17:00–19:00</div><div class="subject-badge s-cse2258">CSE2258 — Web Tech (deploy mini demo)</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="subject-badge s-mat2501">MAT2501 — Light revision</div></div></td>
        <td class="note">Simulate test conditions (timed practice) for Python + DCN.</td>
      </tr>

      <!-- 06-10 -->
      <tr>
        <td>06-10-2025</td>
        <td>Monday</td>
        <td><div class="slot"><div class="time">08:00–11:00</div><div class="subject-badge s-cse1500">CSE1500 — Full revision (must-know list)</div></div></td>
        <td><div class="slot"><div class="time">13:00–16:00</div><div class="subject-badge s-cse2257">CSE2257 — Full revision (diagrams + MCQs)</div></div></td>
        <td><div class="slot"><div class="time">17:00–19:00</div><div class="subject-badge s-cse2251">CSE2251 — Full revision (key protocols)</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="note">Pack exam kit, sleep early.</div></div></td>
        <td class="note">Focus on highest-yield items for first 3 exams.</td>
      </tr>

      <!-- 07-10 Exam CSE1500 -->
      <tr>
        <td>07-10-2025</td>
        <td>Tuesday</td>
        <td>
          <div class="slot">
            <div class="time">08:00–11:00</div>
            <div class="subject-badge s-cse1500">Quick review — CSE1500 (formulae & one mock)</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">11:45–13:15</div>
            <div class="exam">EXAM: CSE1500 — 11:45am to 01:15pm</div>
          </div>
        </td>
        <td><div class="slot"><div class="time">14:30–16:30</div><div class="note">Rest & light walk → short review of next subject</div></div></td>
        <td><div class="slot"><div class="time">17:00–19:00</div><div class="subject-badge s-cse2257">CSE2257 — Light prep (for tomorrow)</div></div></td>
        <td class="note">After exam: hydrate, short recap of mistakes (if any).</td>
      </tr>

      <!-- 08-10 Exam CSE2257 (AM) & CSE2251 (PM) -->
      <tr>
        <td>08-10-2025</td>
        <td>Wednesday</td>
        <td>
          <div class="slot">
            <div class="time">07:00–09:00</div>
            <div class="subject-badge s-cse2257">Warm-up — CSE2257</div>
          </div>
          <div style="margin-top:6px;">
            <div class="time">09:30–11:00</div>
            <div class="exam">EXAM: CSE2257 — 09:30am to 11:00am</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">14:00–15:30</div>
            <div class="exam">EXAM: CSE2251 — 02:00pm to 03:30pm</div>
          </div>
        </td>
        <td><div class="slot"><div class="time">16:30–18:30</div><div class="subject-badge s-cse2251">CSE2251 — Post-exam recap</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="note">Short data-structures light practice (for next day)</div></div></td>
        <td class="note">Two exam day — keep snacks & stay hydrated between exams.</td>
      </tr>

      <!-- 09-10 Exam CSE2253 -->
      <tr>
        <td>09-10-2025</td>
        <td>Thursday</td>
        <td>
          <div class="slot">
            <div class="time">08:00–11:00</div>
            <div class="subject-badge s-cse2253">CSE2253 — Final prep (sample problems)</div>
          </div>
        </td>
        <td>
          <div class="slot">
            <div class="time">11:45–13:15</div>
            <div class="exam">EXAM: CSE2253 — 11:45am to 01:15pm</div>
          </div>
        </td>
        <td><div class="slot"><div class="time">15:30–17:30</div><div class="subject-badge s-mat2501">MAT2501 — Start quick prep for Friday exam</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="note">Relax & light revision notes</div></div></td>
        <td class="note">Recover after exam — brief review of missed concepts.</td>
      </tr>

      <!-- 10-10 Exam MAT2501 -->
      <tr>
        <td>10-10-2025</td>
        <td>Friday</td>
        <td><div class="slot"><div class="time">09:00–12:00</div><div class="subject-badge s-mat2501">MAT2501 — Focused practice</div></div></td>
        <td><div class="slot"><div class="time">14:00–15:30</div><div class="exam">EXAM: MAT2501 — 02:00pm to 03:30pm</div></div></td>
        <td><div class="slot"><div class="time">17:00–19:00</div><div class="subject-badge s-cse2258">CSE2258 — Light prep for final exam</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="note">Pack items for final exam & sleep early</div></div></td>
        <td class="note">Final exams week — keep calm and follow schedule.</td>
      </tr>

      <!-- 11-10 Exam CSE2258 -->
      <tr>
        <td>11-10-2025</td>
        <td>Saturday</td>
        <td><div class="slot"><div class="time">08:00–11:00</div><div class="subject-badge s-cse2258">Quick review — Web Technologies</div></div></td>
        <td><div class="slot"><div class="time">11:45–13:15</div><div class="exam">EXAM: CSE2258 — 11:45am to 01:15pm</div></div></td>
        <td><div class="slot"><div class="time">15:00–17:00</div><div class="note">Celebrate — you've finished! 🎉</div></div></td>
        <td><div class="slot"><div class="time">20:00–21:00</div><div class="note">Reflect & jot what worked for future plans</div></div></td>
        <td class="note">Congrats — final exam day. Good luck!</td>
      </tr>

    </tbody>
  </table>

  <footer>Tip: Print this page in landscape for best fit. Adjust times to suit your daily rhythm.</footer>
</div>
</body>
</html>
