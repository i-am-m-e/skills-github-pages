---
layout: default
title: Mohamed Elandry, BScN, RN, ENC(C)
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap');

  /* 1. Hide default GitHub Pages / Jekyll theme chrome */
  header,
  footer,
  .site-header,
  .site-footer,
  .page-header,
  .container-lg > h1:first-child,
  .markdown-body > h1:first-child {
    display: none !important;
  }

  /* 2. Reset theme containers & apply premium background */
  html, body {
    margin: 0 !important;
    padding: 0 !important;
    background-color: #f3f5f4 !important;
    background-image:
      radial-gradient(at 0% 0%, rgba(0, 124, 65, 0.07) 0px, transparent 50%),
      radial-gradient(at 100% 0%, rgba(15, 23, 42, 0.06) 0px, transparent 50%) !important;
    color: #0f172a;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
    -webkit-font-smoothing: antialiased;
  }

  .container-lg,
  .wrapper,
  .main-content,
  .markdown-body {
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
  }

  :root {
    --emerald: #007C41;
    --emerald-light: #10b981;
    --deep-forest: #091e17;
    --ink: #0f172a;
    --muted: #475569;
    --surface: #ffffff;
    --border: rgba(15, 23, 42, 0.08);
  }

  .page-shell {
    max-width: 920px;
    margin: 0 auto;
    padding: 2.5rem 1.25rem 4rem;
  }

  /* 3. Premium Dark Hero */
  .hero {
    background: linear-gradient(135deg, #091e17 0%, #102a22 55%, #0f172a 100%);
    color: #ffffff;
    border-radius: 24px;
    padding: 3.5rem 2.25rem;
    text-align: center;
    box-shadow: 0 20px 50px rgba(9, 30, 23, 0.18);
    position: relative;
    overflow: hidden;
  }

  .hero-avatar {
    width: 128px;
    height: 128px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.25);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.35);
    margin-bottom: 1.25rem;
  }

  .hero-eyebrow {
    display: inline-block;
    font-size: 0.78rem;
    font-weight: 600;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #6ee7b7;
    background: rgba(16, 185, 129, 0.12);
    border: 1px solid rgba(110, 231, 183, 0.25);
    padding: 0.35rem 0.9rem;
    border-radius: 999px;
    margin-bottom: 1rem;
  }

  .hero h1 {
    font-family: 'Playfair Display', Georgia, serif;
    font-size: clamp(2rem, 4vw, 2.75rem);
    font-weight: 700;
    color: #ffffff !important;
    margin: 0 0 0.6rem;
    line-height: 1.15;
    border: none !important;
  }

  .hero-subtitle {
    font-size: 1.05rem;
    color: #cbd5e1;
    max-width: 620px;
    margin: 0 auto 1.75rem;
    line-height: 1.6;
  }

  /* Buttons */
  .btn-group {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 0.75rem;
  }

  .btn {
    display: inline-block;
    padding: 0.7rem 1.45rem;
    border-radius: 999px;
    font-size: 0.9rem;
    font-weight: 600;
    text-decoration: none !important;
    transition: all 0.2s ease;
  }

  .btn:hover {
    transform: translateY(-2px);
  }

  .btn-primary {
    background: var(--emerald-light);
    color: #06281c !important;
    box-shadow: 0 6px 20px rgba(16, 185, 129, 0.3);
  }

  .btn-primary:hover {
    background: #34d399;
  }

  .btn-glass {
    background: rgba(255, 255, 255, 0.08);
    color: #ffffff !important;
    border: 1px solid rgba(255, 255, 255, 0.2);
  }

  .btn-glass:hover {
    background: rgba(255, 255, 255, 0.16);
  }

  /* 4. Key Metrics Strip */
  .stats-bar {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
    gap: 1rem;
    margin: 1.5rem 0 2.5rem;
  }

  .stat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 1.2rem 1rem;
    text-align: center;
    box-shadow: 0 4px 16px rgba(15, 23, 42, 0.03);
  }

  .stat-value {
    font-family: 'Playfair Display', Georgia, serif;
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--emerald);
    line-height: 1.2;
  }

  .stat-label {
    font-size: 0.8rem;
    font-weight: 500;
    color: var(--muted);
    margin-top: 0.25rem;
  }

  /* 5. Content Sections */
  .section-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 2rem;
    margin-bottom: 1.75rem;
    box-shadow: 0 6px 24px rgba(15, 23, 42, 0.04);
  }

  .section-title {
    font-family: 'Playfair Display', Georgia, serif;
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--ink) !important;
    margin: 0 0 1.25rem !important;
    padding-bottom: 0.6rem;
    border-bottom: 1px solid var(--border) !important;
  }

  .section-card p {
    color: #334155;
    font-size: 0.98rem;
    line-height: 1.75;
    margin: 0 0 1rem;
  }

  .section-card p:last-child {
    margin-bottom: 0;
  }

  /* 2-Column Focus Grid */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.25rem;
  }

  .focus-card {
    background: #f8faf9;
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 1.5rem;
    transition: transform 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease;
  }

  .focus-card:hover {
    transform: translateY(-3px);
    border-color: rgba(0, 124, 65, 0.35);
    box-shadow: 0 10px 25px rgba(0, 124, 65, 0.07);
  }

  .focus-card h3 {
    margin: 0 0 0.5rem !important;
    font-size: 1.05rem;
    font-weight: 700;
    color: var(--emerald) !important;
  }

  .focus-card p {
    margin: 0;
    font-size: 0.92rem;
    color: var(--muted);
    line-height: 1.65;
  }

  /* Highlights & Credentials */
  .highlight-list {
    list-style: none !important;
    padding: 0 !important;
    margin: 0 !important;
  }

  .highlight-list li {
    padding: 0.85rem 0;
    border-bottom: 1px solid var(--border);
    font-size: 0.95rem;
    color: #334155;
  }

  .highlight-list li:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }

  .pill-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-top: 1.5rem;
    padding-top: 1.25rem;
    border-top: 1px solid var(--border);
  }

  .pill {
    background: #ecfdf5;
    color: #065f46;
    border: 1px solid #a7f3d0;
    font-size: 0.8rem;
    font-weight: 600;
    padding: 0.35rem 0.85rem;
    border-radius: 999px;
  }

  /* 6. Collaboration CTA */
  .collab-box {
    background: linear-gradient(135deg, #0f172a 0%, #091e17 100%);
    color: #f8fafc;
    border-radius: 22px;
    padding: 2.5rem 2.25rem;
    box-shadow: 0 18px 40px rgba(15, 23, 42, 0.14);
  }

  .collab-box h2 {
    font-family: 'Playfair Display', Georgia, serif;
    font-size: 1.65rem;
    color: #ffffff !important;
    margin: 0 0 0.75rem !important;
    border: none !important;
  }

  .collab-box p,
  .collab-box li {
    color: #cbd5e1;
    font-size: 0.95rem;
    line-height: 1.7;
  }

  .collab-box ul {
    padding-left: 1.2rem;
    margin: 1rem 0 1.75rem;
  }

  .collab-box li {
    margin-bottom: 0.5rem;
  }

  .collab-box strong {
    color: #ffffff;
  }

  .site-footer-note {
    text-align: center;
    font-size: 0.82rem;
    color: #64748b;
    margin-top: 2.5rem;
  }
</style>

<div class="page-shell">

  <section class="hero">
    <img src="profile.jpg" alt="Mohamed Elandry" class="hero-avatar" onerror="this.style.display='none'" />
    <div><span class="hero-eyebrow">Edmonton, Alberta · University of Alberta</span></div>
    <h1>Mohamed Elandry, BScN, RN, ENC(C)</h1>
    <p class="hero-subtitle">
      Nurse Practitioner Student, Emergency &amp; Urgent Care Leader, and Health AI Researcher bridging frontline clinical care with human-centered innovation.
    </p>
    <div class="btn-group">
      <a href="mailto:moheland@ualberta.ca" class="btn btn-primary">Get in Touch</a>
      <a href="https://linkedin.com/in/mohamed-elandry" class="btn btn-glass" target="_blank">LinkedIn</a>
      <a href="https://github.com/i-am-m-e" class="btn btn-glass" target="_blank">GitHub</a>
    </div>
  </section>

  <div class="stats-bar">
    <div class="stat-card">
      <div class="stat-value">12,500+</div>
      <div class="stat-label">Clinical Hours</div>
    </div>
    <div class="stat-card">
      <div class="stat-value">4.0 / 4.0</div>
      <div class="stat-label">MN (NP) GPA</div>
    </div>
    <div class="stat-card">
      <div class="stat-value">ENC(C)</div>
      <div class="stat-label">Emergency Certified</div>
    </div>
    <div class="stat-card">
      <div class="stat-value">AI + Health</div>
      <div class="stat-label">Ethics &amp; QI Research</div>
    </div>
  </div>

  <section class="section-card">
    <h2 class="section-title">About Me</h2>
    <p>
      I’m a <strong>Master of Nursing (Nurse Practitioner — Family/All Ages)</strong> student at the
      <strong>University of Alberta</strong> and an <strong>Assistant Head Nurse</strong> in Family &amp; Urgent Care
      at the East Edmonton Health Centre.
    </p>
    <p>
      With over <strong>12,500 clinical hours</strong> across urban trauma centres, urgent care, and rural Northern Alberta
      emergency departments, my work sits at the intersection of <strong>frontline clinical excellence, health technology, and nursing education</strong>.
      Whether I’m teaching ultrasound-guided IV access, investigating the ethics of AI scribes in emergency medicine, or exploring
      existentialist frameworks for nurse burnout, I’m driven by one question: <em>how do we build healthcare systems where both
      patients and clinicians can thrive?</em>
    </p>
  </section>

  <section class="section-card">
    <h2 class="section-title">Focus Areas &amp; Current Work</h2>
    <div class="card-grid">
      <div class="focus-card">
        <h3>Health AI &amp; Ethics</h3>
        <p>
          Graduate Research Assistant investigating the <strong>ethics of AI scribes in Edmonton Emergency Departments</strong>
          (U of A Faculty of Nursing). Member of the AI + Health Hub and national CASN webinar panelist on AI in graduate nursing.
        </p>
      </div>
      <div class="focus-card">
        <h3>Clinical Leadership &amp; QI</h3>
        <p>
          Assistant Head Nurse &amp; Staff Educator leading Connect Care optimization, the <strong>Complex Care Pathway</strong>
          quality improvement initiative for underserved populations, and provincial ED working groups.
        </p>
      </div>
      <div class="focus-card">
        <h3>Research &amp; Philosophy</h3>
        <p>
          Co-Investigator on a national survey of <strong>critical incident reporting</strong> in Canadian undergraduate nursing.
          Sole author of a manuscript applying <strong>existentialist philosophy</strong> (Sartre, Camus, Heidegger, Merleau-Ponty) to nurse burnout.
        </p>
      </div>
      <div class="focus-card">
        <h3>Teaching &amp; Mentorship</h3>
        <p>
          Graduate Teaching Assistant (Indigenous Health; Anatomy &amp; Physiology), POCUS IV instructor, Elsevier peer reviewer,
          and MentorUs peer mentor for graduate nursing students.
        </p>
      </div>
    </div>
  </section>

  <section class="section-card">
    <h2 class="section-title">Selected Highlights &amp; Credentials</h2>
    <ul class="highlight-list">
      <li><strong>2026 Karen Polowick Leadership Award</strong> — Alberta Registered Nurses Educational Trust (ARNET)</li>
      <li><strong>National Panelist (CASN, 2026)</strong> — <em>AI Use in Learning in Graduate Studies</em></li>
      <li><strong>Lead Presenter &amp; Co-Facilitator</strong> — <em>"See It, Stick It: POCUS IV"</em>, Provincial Urgent Care Conference</li>
      <li><strong>Conference Presenter (U of A, 2026)</strong> — <em>"Know Thyself: Existentialism as a Response to Depersonalization in Nursing Practice"</em></li>
    </ul>
    <div class="pill-row">
      <span class="pill">ENC(C)</span>
      <span class="pill">POCUS IV/IO Instructor</span>
      <span class="pill">ACLS · PALS · TNCC · CTAS · NRP</span>
      <span class="pill">AHS Improvement Way (QI)</span>
      <span class="pill">Health Care Management</span>
    </div>
  </section>

  <section class="collab-box">
    <h2>Let’s Collaborate</h2>
    <p>I’m always open to connecting with clinicians, researchers, educators, and health-tech builders. Reach out if you’re interested in:</p>
    <ul>
      <li><strong>Health AI &amp; Digital Health:</strong> Qualitative research, workflow integration, or ethical evaluation of AI in acute/primary care.</li>
      <li><strong>Nursing &amp; Medical Education:</strong> POCUS workshops, curriculum innovation, or graduate mentorship.</li>
      <li><strong>Quality Improvement &amp; Health Equity:</strong> Expanding preventive care pathways and improving patient/clinician experiences.</li>
      <li><strong>Speaking &amp; Writing:</strong> Panels, interdisciplinary conferences, or manuscripts at the intersection of healthcare, tech, and humanities.</li>
    </ul>
    <div class="btn-group" style="justify-content: flex-start;">
      <a href="mailto:moheland@ualberta.ca" class="btn btn-primary">Email Mohamed</a>
      <a href="https://linkedin.com/in/mohamed-elandry" class="btn btn-glass" target="_blank">Connect on LinkedIn</a>
    </div>
  </section>

  <div class="site-footer-note">
    Mohamed Elandry · Edmonton, Alberta · University of Alberta Faculty of Nursing
  </div>

</div>
