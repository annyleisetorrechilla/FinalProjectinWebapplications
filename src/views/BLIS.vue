<script setup>
import BLISlogo from '../assets/LISSO-150x150.png'
</script>

<template>
  <main class="computer-science-page">
    <section class="intro">
      <div class="intro-backdrop" aria-hidden="true">
        <img :src="BLISlogo" alt="" />
      </div>
      <div class="intro-copy">
        <p class="eyebrow">Academic Program · BLIS</p>
        <h1>Library Information Science</h1>
        <p class="lead">
          The Degree of Bachelor of Library and Information Science (BLIS) is a four-year program that prepares students in the development, deployment, and management of information resources in print, non-print, electronic, and digital formats.
        </p>
        <nav class="page-actions" aria-label="Library Information Science page sections">
          <a class="section-button" href="#objectives">Objectives</a>
          <a class="section-button" href="#campus-life">Campus Life</a>
        </nav>
      </div>
    </section>

    <div class="content-sections">
      <section id="objectives" class="content-card" aria-labelledby="objectives-heading">
        <h2 id="objectives-heading">Program Educational Objectives</h2>
        <ol>
          <li>
            Exhibit skills, knowledge and leadership to excel in their information technology careers and related discipline.
          </li>
          <li>
            Exhibit high standard of professionalism who are effective members of multi-discipline development teams
          </li>
          <li>
            Involved in scholarly activities, research and outreach that contributes to the improvement and transformation of society
          </li>
          <li>
            Demonstrate ethical, professional, spiritual values, and social responsibility associated with their Information Technology careers and related professions.
          </li>
          <li>
            Exhibit proficiency in the use of traditional and digital media arts, designing, developing and implementing digital media solutions in fields of entertainment and corporate environments.
          </li>
        </ol>

        <nav class="objectives-subnav" aria-label="Library Information Science program information">
          <a href="#po">Program Outcomes</a>
          <a href="#rat">Curriculum Rationale</a>
          <a href="#desc">Curriculum Description</a>
          <a href="#so">Student Organization</a>
          <a href="#go">Graduate Outcomes</a>
        </nav>
      </section>

      <section
        id="po"
        class="content-card information-section"
        aria-labelledby="program-outcomes-heading"
      >
          <h3 id="program-outcomes-heading">Program Outcomes</h3>
          <h4>The graduates have the ability to</h4>
          <ol type="a">
            <li>
              articulate and  discuss the  latest developments  in the  specific field  of practice.    (Philippine Qualifications Framework (PQF) level 6 descriptor)  (Graduate Outcomes:  CS 10, IS 10, IT13). 
            </li>
            <li>
              effectively communicate orally and in writing using both English and Filipino (Graduate Outcomes:  CS08,  1508,  IT10).
            </li>
            <li>
              work effectively  and  independently  in   multi-disciplinary  and multi-cultural teams. (PQF level 6 descriptor) (Graduate Outcomes:  CS07, ISO?, IT08).  
            </li>
            <li>
              act in recognition of professional, social and ethical responsibility (Graduate Outcomes:CS09, 1509,  IT12)
            </li>
            <li>
              preserve and promote “Filipino  historical  and cultural heritage” (based  on RA 7722). 
            </li>
          </ol>
      </section>

      <section
        id="rat"
        class="content-card information-section"
        aria-labelledby="rationale-heading"
      >
          <h3 id="rationale-heading">Curriculum Rationale</h3>
          <p class="rationale-copy">
            Based on he Guidelines for the Implementation of CMO 46 s. 2012, this PSG implements the “shift to learning competency-based standards/outcomes-based education”. It specifies the “core competencies” expected of Bachelor of Library and Information Science (BLIS) graduates regardless of the type of HEI they graduate from. However, in recognition of the spirit of outcomes-based education-which puts premium in the achievement of learning outcomes through different strategies-and in recognition of the typology of HEIs, this PSG also provides ample space for HEIs to innovate in the curriculum, in line with the assessment of how best to achieve learning outcomes in their particular contexts and their respective missions.

Policies and standards int he Library and Information Science (LIS) program are necessary for the highest level of quality desired for the education and training of library and information science professionals. They are meant to institutionalize the profession’s central function of providing quality information service to library/information center clientele or users. Its purpose is to make LIS education responsive to the challenges of society’s changing information needs brought about by rapid technological changes and in keeping with the need to make LIS professionals globally competitive. 
          </p>
      </section>

      <section
        id="desc"
        class="content-card information-section"
        aria-labelledby="curriculum-heading"
      >
          <h3 id="curriculum-heading">Curriculum Description</h3>
          <ul>
            <li>
              The LIS curriculum is designed to equip the professional with the composite knowledge, skills, attitudes, and tools to enable him/her to be responsive to the changing information needs of society.
            </li>
            <li class="curriculum-society-copy">
              The Computer Science Society embraces its Mission to promote the Computer Science Course, to guide and prepare the students, to grow and strengthen the bonds of each member as one family, and to utilize the resources of the program to provide service to society and emphasize to students the need of lifelong learning, ethical conduct and an understanding of the diverse social context in which Computer Science is practiced. We furthermore seek to provide excellence in activities and outreaches to develop the community of all Computer Science Students to help and support its members to reach their goals in the ever advance, 21st century.
            </li>
            <li>Defines eleven (11) Knowledge Areas:</li>
          </ul>
          <ul class="knowledge-areas">
            <li>Algorithms and Complexity</li>
            <li>Architecture and Organization</li>
            <li>Discreet Structures</li>
            <li>Human Computer Interaction</li>
            <li>Information Assurance and Security</li>
            <li>Networks and Communications</li>
            <li>Operating Systems</li>
            <li>Programming Languages (Design and Implementation)</li>
            <li>Software Development Fundamentals</li>
            <li>Software Engineering</li>
            <li>Social Issues and Professional Practice</li>
          </ul>
      </section>

      <section id="campus-life" class="content-card" aria-labelledby="campus-life-heading">
        <span id="so" class="anchor-target"></span>
        <h2 id="campus-life-heading">Student Organization and Campus Life</h2>
        <img
          class="organization-logo"
          :src="BLISlogo"
          alt="Library and Information Science Student Organization logo"
        />
        <p class="campus-life-copy">
          The Computer Science Society embraces its Mission to promote the Computer Science Course, to guide and prepare the students, to grow and strengthen the bonds of each member as one family, and to utilize the resources of the program to provide service to society and emphasize to students the need of lifelong learning, ethical conduct and an understanding of the diverse social context in which Computer Science is practiced. We furthermore seek to provide excellence in activities and outreaches to develop the community of all Computer Science Students to help and support its members to reach their goals in the ever advance, 21st century.
        </p>
      </section>

      <section
        id="go"
        class="content-card information-section graduate-outcomes"
        aria-labelledby="graduate-outcomes-heading"
      >
          <h3 class="degree-heading">Bachelor of Science in Information Systems (BSIS)</h3>
          <h4 id="graduate-outcomes-heading">Graduate Outcomes</h4>
          <div class="outcomes-table-wrap">
            <table class="outcomes-table">
              <thead>
                <tr>
                  <th scope="col">Code</th>
                  <th scope="col">Graduate Outcomes</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th scope="row">LIS01</th>
                  <td>
                    Select, evaluate, organize and disseminate print, multimedia, electronic and digital information resources.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS02</th>
                  <td>
                    Effectively communicate orally and in writing, at the same time, use a variety of    communication methods in a manner that best enables the message to be understood.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS03</th>
                  <td>
                    Demonstrate logical and systematic approaches to the accomplishment of tasks.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS04</th>
                  <td>
                    Formulate objectives, policies and processes as well as design and manage resources in anticipation of future educational or organizational changes.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS05</th>
                  <td>
                    Recognize, analyze and constructively solve problems, provide appropriate direction and assistance, and overcome barriers when necessary.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS06</th>
                  <td>
                    Identify users’ needs and wants through reference interviews, customer surveys, complaint logs and other means in order to evaluate the effectiveness of current services and improve these and other practices.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS07</th>
                  <td>
                    Work well in groups and seek ways to build team efforts to solve problems and achieve common goals.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS08</th>
                  <td>
                    Understand library’s automation system and the use of computer hardware, software and peripherals, including online collaboration tools (the internet, the worldwide web, and social networking sites).
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS09</th>
                  <td>
                    Develop information technology solutions (e.g., library automation system, Website, e-mail system, etc.).
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS10</th>
                  <td>
                    Conduct significant research projects that will benefit the library and the organization.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS11</th>
                  <td>
                    Evaluate and debate information policy (e.g., copyright law, plagiarism, cybercrimes, etc.) and ethical issues applicable in local, national or global context.
                  </td>
                </tr>
                <tr>
                  <th scope="row">LIS12</th>
                  <td>
                    Participate in continuing education activities organized by library associations and other entities.
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <blockquote class="program-quote">
            “An academic program with a talent-centric curriculum for the high-end digital media industry.”
          </blockquote>
      </section>
    </div>
  </main>
</template>

<style scoped>
.computer-science-page {
  --program-accent: #42a6cf;
  --program-accent-soft: #e8f7fc;
  min-height: 100vh;
  padding: 0 1.5rem 4rem;
  background: #f8fafc;
  color: #25364a;
}

.intro {
  position: relative;
  isolation: isolate;
  display: grid;
  min-height: 470px;
  align-items: center;
  overflow: hidden;
  margin-inline: -1.5rem;
  padding: 3.5rem max(1.5rem, calc((100vw - 720px) / 2));
  color: #1f2937;
  text-align: center;
}

.intro-backdrop {
  position: absolute;
  z-index: -1;
  inset: 0;
  display: grid;
  place-items: center;
  overflow: hidden;
  background:
    radial-gradient(ellipse at 62% 48%, rgba(255, 255, 255, 0.45), transparent 48%),
    #d1d5db;
}

.intro-backdrop img {
  width: min(55vw, 520px);
  height: min(55vw, 520px);
  object-fit: cover;
  opacity: 0.24;
  filter: grayscale(1) contrast(1.15);
  transform: rotate(-12deg) scale(.9);
}

.intro-copy {
  max-width: 720px;
  margin: 0 auto;
}

.eyebrow {
  margin: 0 0 0.65rem;
  color: #4b5563;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

h1 {
  margin: 0;
  color: #111827;
  font-size: clamp(1.8rem, 4vw, 2.5rem);
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: -0.025em;
}

.lead {
  max-width: 620px;
  margin: 0.9rem auto 0;
  color: #374151;
  font-size: 0.95rem;
  line-height: 1.7;
}

.page-actions {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.75rem;
  margin-top: 1.25rem;
}

.section-button {
  padding: 0.25rem 0;
  color: #1f2937;
  font-size: 0.85rem;
  font-weight: 600;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s ease, color 0.2s ease;
}

.section-button:hover,
.section-button:focus-visible {
  border-color: currentColor;
  color: #374151;
}

.content-sections {
  max-width: 1100px;
  margin: 0 auto;
}

.content-card {
  min-width: 0;
  scroll-margin-top: 5rem;
  padding: 2rem 0;
  border-bottom: 1px solid #e3e8ee;
}

.section-label {
  margin: 0 0 0.8rem;
  color: #42617f;
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-align: center;
  text-transform: uppercase;
}

.content-card h2 {
  margin: 0;
  color: #153b5b;
  font-size: 1.12rem;
  font-weight: 700;
  text-align: center;
}

.content-card > p:last-child {
  margin: 1rem 0 0;
  color: #251e30;
  font-size: 0.9rem;
  line-height: 1.75;
}

.campus-life-copy {
  color: #251e30;
  font-size: 0.9rem;
  line-height: 1.75;
}

.content-card ol {
  display: grid;
  gap: 0.45rem;
  margin: 1rem 0 0;
  padding-left: 1.25rem;
  color: #251e30;
  font-size: 0.86rem;
  line-height: 1.65;
}

.objectives-subnav {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.45rem 1rem;
  margin-top: 1.5rem;
  padding: 0.75rem 0 0;
}

.objectives-subnav a {
  color: #251e30;
  font-size: 0.8rem;
  font-weight: 600;
  text-decoration-color: #9aabba;
  text-underline-offset: 0.2em;
}

.information-section {
  scroll-margin-top: 5rem;
}

.information-section h3 {
  margin: 0;
  color: #251e30;
  font-size: 1.05rem;
  font-weight: 700;
}

.information-section .degree-heading {
  text-align: center;
}

#po h3 {
  text-align: center;
  text-transform: uppercase;
}

.information-section h4 {
  margin: 1.1rem 0 0;
  color: #251e30;
  font-size: 0.9rem;
  font-weight: 700;
}

.information-section p,
.information-section li {
  color: #251e30;
  line-height: 1.7;
}

.information-section p {
  margin: 0.8rem 0 0;
  font-size: 0.86rem;
}

.information-section ol,
.information-section ul {
  display: grid;
  gap: 0.35rem;
  margin: 0.65rem 0 0;
  padding-left: 1.25rem;
  font-size: 0.82rem;
}

.information-section .knowledge-areas {
  grid-template-columns: repeat(2, minmax(0, 1fr));
  padding-left: 0;
  list-style: none;
}

.information-section .knowledge-areas li {
  position: relative;
  padding-left: 1.25rem;
}

.information-section .knowledge-areas li::before {
  position: absolute;
  left: 0;
  content: '-';
}

.outcomes-table-wrap {
  overflow-x: auto;
  margin-top: 0.75rem;
}

.outcomes-table {
  width: 100%;
  border-collapse: collapse;
  color: #251e30;
  font-size: 0.82rem;
  line-height: 1.65;
}

.outcomes-table th,
.outcomes-table td {
  padding: 0.65rem 0.75rem;
  border-bottom: 1px solid #e3e8ee;
  text-align: left;
  vertical-align: top;
}

.outcomes-table thead th {
  background: #f5f8fa;
  color: #251e30;
}

.outcomes-table tbody th {
  width: 4.5rem;
  color: #251e30;
  text-align: left;
  white-space: nowrap;
}

.program-quote {
  margin: 1.5rem 0 0;
  padding: 0 0 0 1rem;
  border-left: 2px solid #9aabba;
  color: #251e30;
  font-size: 0.9rem;
  font-style: italic;
}

.organization-logo {
  width: 99px;
  height: 99px;
  margin: 1rem auto;
  object-fit: contain;
}

.source-note {
  font-size: 0.8rem;
  font-style: italic;
  text-align: center;
}

.information-section p.source-note {
  text-align: center;
}

.anchor-target {
  display: block;
  scroll-margin-top: 5rem;
}

.content-sections {
  max-width: 1100px;
  gap: 1rem;
  padding: 2rem 0;
}

.content-card {
  grid-column: 1 / -1;
  padding: clamp(1.5rem, 4vw, 2.5rem);
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(31, 41, 55, 0.07);
}

.content-card h2,
.information-section h3 {
  color: var(--program-accent);
}

.objectives-subnav a {
  color: var(--program-accent);
}

.outcomes-table thead th {
  background: var(--program-accent);
}

.outcomes-table tbody th {
  color: var(--program-accent);
}

.program-quote {
  border-left-color: var(--program-accent);
  border-radius: 0 8px 8px 0;
  background: var(--program-accent-soft);
}

.content-card > ol,
.content-card > ul {
  font-size: 0.86rem;
  line-height: 1.65;
  text-align: justify;
}

.information-section h3 {
  font-size: 1.05rem;
  font-weight: 700;
}

.information-section h4 {
  font-size: 0.9rem;
}

.information-section p,
.information-section li {
  font-size: 0.86rem;
  line-height: 1.7;
  text-align: justify;
}

.information-section ol,
.information-section ul {
  font-size: 0.82rem;
  line-height: 1.7;
}

.outcomes-table-wrap {
  width: 100%;
  max-width: none;
  margin-inline: 0;
}

.outcomes-table td {
  text-align: justify;
}

.graduate-outcomes h4,
#graduate-outcomes h4 {
  text-align: center;
}

.page-actions {
  justify-content: center;
  gap: 0.85rem;
}

.intro .section-button {
  padding: 0.65rem 1rem;
  border: 1px solid var(--program-accent);
  border-radius: 6px;
  background: #ffffff;
  color: var(--program-accent);
  transition: background-color 0.2s ease, color 0.2s ease, transform 0.2s ease;
}

.intro .section-button:hover,
.intro .section-button:focus-visible {
  border-color: var(--program-accent);
  background: var(--program-accent);
  color: #ffffff;
  transform: translateY(-1px);
}

.objectives-subnav {
  justify-content: center;
  text-align: center;
}

.content-card h2,
.information-section h2,
.information-section h3,
.information-section h4 {
  font-family: inherit;
  text-align: center;
}

.content-card h2 {
  font-size: 1.12rem;
  font-weight: 700;
}

.information-section h3 {
  font-size: 1.05rem;
  font-weight: 700;
}

.information-section h4 {
  font-size: 0.9rem;
  color: #6b7280;
}

.graduate-outcomes h4,
#go h4 {
  color: #6b7280;
  text-align: center;
}

.outcomes-table thead th {
  text-align: center;
}

.program-quote {
  text-align: center;
}

@media (max-width: 640px) {
  .computer-science-page {
    padding: 0 1rem 2.5rem;
  }

  .intro {
    min-height: 440px;
    margin-inline: -1rem;
    padding: 5rem 1.25rem 2rem;
  }

  .intro-backdrop img {
    width: 115vw;
    height: 115vw;
  }

  .eyebrow {
    font-size: 0.68rem;
  }

  h1 {
    font-size: clamp(1.65rem, 7vw, 2.1rem);
  }

  .lead {
    font-size: 0.9rem;
    line-height: 1.6;
  }

  .content-card {
    padding: 1.5rem 0;
  }

  .content-card h2 {
    font-size: 1.05rem;
  }

  .content-card ol {
    padding-left: 1.1rem;
    font-size: 0.82rem;
  }

  .objectives-subnav a {
    font-size: 0.76rem;
  }

  .outcomes-table-wrap {
    margin-inline: -0.25rem;
    -webkit-overflow-scrolling: touch;
  }

  .outcomes-table {
    font-size: 0.78rem;
  }

  .outcomes-table th,
  .outcomes-table td {
    padding: 0.5rem 0.4rem;
  }

  .outcomes-table tbody th {
    width: 4rem;
  }

  .information-section .knowledge-areas {
    grid-template-columns: 1fr;
  }
}

.computer-science-page {
  font-family: Poppins, sans-serif;
  font-size: 12px;
  font-style: normal;
}

.computer-science-page h1 {
  font-size: 35px;
}

.computer-science-page h2,
.computer-science-page h3,
.computer-science-page h4 {
  font-size: 20px;
}

.computer-science-page p,
.computer-science-page li,
.computer-science-page td,
.computer-science-page th,
.computer-science-page a,
.computer-science-page blockquote {
  font-family: inherit;
  font-size: 12px;
}

.computer-science-page .information-section p.rationale-copy,
.computer-science-page .information-section li.curriculum-society-copy,
.computer-science-page .campus-life-copy {
  font-size: 12px;
}
</style>
