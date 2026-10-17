<script setup>
import DMIAlogo from '../assets/MIDAS_PNG-150x150.png'
</script>

<template>
  <main class="computer-science-page">
    <section class="intro">
      <div class="intro-backdrop" aria-hidden="true">
        <img :src="DMIAlogo" alt="" />
      </div>
      <div class="intro-copy">
        <p class="eyebrow">Academic Program · BSDMIA</p>
        <h1>Digital Media and Interactive Arts</h1>
        <p class="lead">
          The Degree of Bachelor of Science in Digital Media and Interactive Arts is focused on creativity, applied arts and digital media technologies.
        </p>
        <nav class="page-actions" aria-label="Digital Media and Interactive Arts page sections">
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
            Exhibit proficiency in the use of traditional and digital media arts, 
            designing, developing and implementing digital media solutions in fields of 
            entertainment and corporate environments
          </li>
        </ol>

        <nav class="objectives-subnav" aria-label="Digital Media and Interactive Arts program information">
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
              articulate and  discuss the  latest developments  in the  specific field  of practice.    
              (Philippine Qualifications Framework (PQF) level 6 descriptor)  (Graduate Outcomes:  DMIA 10, IS 10, IT13). 
            </li>
            <li>
              effectively communicate orally and in writing using both English 
              and Filipino (Graduate Outcomes:  DMIA08,  1508,  IT10). 
            </li>
            <li>
              work effectively  and  independently  in   
              multi-disciplinary  and multi-cultural teams. (PQF level 6 descriptor) (Graduate Outcomes:  DMIA07, ISO?, IT08). 
            </li>
            <li>
              Act in recognition of professional, social and ethical responsibility
              (Graduate Outcomes:DMIA09, 1509, IT12).
            </li>
            <li>Preserve and promote “Filipino historical and cultural heritage” (based on RA 7722).</li>
          </ol>
      </section>

      <section
        id="rat"
        class="content-card information-section"
        aria-labelledby="rationale-heading"
      >
          <h3 id="rationale-heading">Curriculum Rationale</h3>
          <p class="rationale-copy">
            The Bachelor of Science in Digital Media and Interactive Arts (BSDMIA) program is offered based on CMO 19 s 2016 article iii section 11 which states that an autonomous institution has the privilege to offer new course(s)/program(s) in the undergraduate and/or graduate levels. 
            Along with this is the effect of technology in the field of arts and other art related careers. Careers in the field of information technology education (ITE) has expanded in the area of art. This has long been integrated in the ITE programs when multimedia was considered as one of its free elective course.
            As defined in the animation career review site, interactive arts and media discipline combines the elements of arts, design and technology. Artist in the field typically have advanced skills in the areas of visual design, digital storytelling, time-based media, and shaping interactive experiences. 
            Such is applied in animation to mobile communications to video games.
            In the program the students are introduced to industry standard tools applications in video editing, animation, 3d modeling, photography, graphic design, video game design and virtual reality.
            Graduates of the program can have careers in advertising agencies, game design companies, pre- and post – production houses, graphic design firms, art studios, mobile communication companies, magazines, publishers, and web design companies. They can be animator, graphic designer, game designer, web designer, multi-media artist, advertising executive, art director, digital artists, and freelance artist.
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
              The Degree of Bachelor of Science in Digital Media and Interactive Arts is focused on creativity, applied arts and digital media technologies. It is designed to developing creative talents for a variety of applied arts industries, including but not limited to the entertainment, education, advertising and commercials, films and corporate communications sectors.
            </li>
            <li>
              The curriculum should include courses to cover Knowledge Areas recommended in ACM
              Computer Science Curricula 2013 (enumerated in PSG).
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
          :src="DMIAlogo"
          alt="Computer Science Society logo"
        />
        <p class="campus-life-copy">
          The Computer Science Society embraces its Mission to promote the Computer Science Course,
          to guide and prepare the students, to grow and strengthen the bonds of each member as one
          family, and to utilize the resources of the program to provide service to society and
          emphasize to students the need of lifelong learning, ethical conduct and an understanding
          of the diverse social context in which Computer Science is practiced. We furthermore seek
          to provide excellence in activities and outreaches to develop the community of all
          Computer Science Students to help and support its members to reach their goals in the
          ever advance, 21st century.
        </p>
      </section>

      <section
        id="go"
        class="content-card information-section graduate-outcomes"
        aria-labelledby="graduate-outcomes-heading"
      >
          <h3 class="degree-heading">Bachelor of Science in Computer Science (BSDMIA)</h3>
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
                  <th scope="row">DMIA01</th>
                  <td>
                    Apply knowledge of mathematics, digital media arts exhibit and management, and digital media creation, delivery and 
                    consumption appropriate to the field of practice in compliance to established standards and best practices
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA02</th>
                  <td>
                    Identify user requirements leading to design selection, digital media art creation, evaluation and delivery of digital media- and interactive arts-based solutions
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA03</th>
                  <td>
                    Design, merge and bridge traditional arts with digital media
                    choices.
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA04</th>
                  <td>
                    Deliver and implement creations, and evaluate digital media consumption in entertainment and corporate environments effectively
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA05</th>
                  <td>
                    Demonstrate the use of current techniques, skills, tools and practices
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA06</th>
                  <td>
                    Function effectively as an individual and as a member or leader in diverse teams and in multidisciplinary settings
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA07</th>
                  <td>
                    Recognize professional, ethical, legal, security, and social issues and responsibility
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA08</th>
                  <td>
                    Socially communicate effectively with a diverse audience
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA09</th>
                  <td>
                    Identify contemporary practices and issues
                  </td>
                </tr>
                <tr>
                  <th scope="row">DMIA10</th>
                  <td>
                    Recognize the need for and engage in planning self-learning and improving performance as a foundation for continuing professional development.
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
  --program-accent: #7951a5;
  --program-accent-soft: #f4ebfb;
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
  color: #f8fafc;
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
    radial-gradient(ellipse at 62% 48%, rgba(227, 227, 227, 0.12), transparent 48%),
    #4f4066;
}

.intro-backdrop img {
  width: min(50vw, 500px);
  height: min(50vw, 500px);
  object-fit: cover;
  opacity: 0.075;
  filter: grayscale(1) brightness(2.2);
  transform: rotate(-12deg) scale(.9);
}

.intro-copy {
  max-width: 720px;
  margin: 0 auto;
}

.eyebrow {
  margin: 0 0 0.65rem;
  color: #cbd5d1;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

h1 {
  margin: 0;
  color: #f8fafc;
  font-size: clamp(1.8rem, 4vw, 2.5rem);
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: -0.025em;
}

.lead {
  max-width: 620px;
  margin: 0.9rem auto 0;
  color: #e3e3e3;
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
  color: #f8fafc;
  font-size: 0.85rem;
  font-weight: 600;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s ease, color 0.2s ease;
}

.section-button:hover,
.section-button:focus-visible {
  border-color: currentColor;
  color: #ffc247;
}

.content-sections {
  max-width: 720px;
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
  width: min(100%, 900px);
  margin-inline: auto;
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
.computer-science-page .campus-life-copy {
  font-size: 12px;
}
</style>
