<script setup>
import computerScienceLogo from '../assets/CSS_PNG-150x150.png'
import informationTechnologyLogo from '../assets/1-150x150.png'
import digitalMediaLogo from '../assets/MIDAS_PNG-150x150.png'
import libraryScienceLogo from '../assets/LISSO-150x150.png'

const programs = [
  {
    code: 'BSCS',
    title: 'Computer Science',
    description:
      'The Computer Science (CS) Program is designed for students who want to study computing in depth, focusing on software and hardware.',
    logo: computerScienceLogo,
    logoAlt: 'Computer Science Society logo',
    route: '/computer-science',
    accent: '#2878c7',
  },
  {
    code: 'BSIT',
    title: 'Information Technology',
    description:
      'The Information Technology (IT) program is designed to bridge the gap between computer science and management information systems.',
    logo: informationTechnologyLogo,
    logoAlt: 'Information Technology Society logo',
    route: '/information-technology',
    accent: '#d5a600',
  },
  {
    code: 'BSDMIA',
    title: 'Digital Media and Interactive Arts',
    description:
      'The Degree of Bachelor of Science in Digital Media and Interactive Arts is focused on creativity, applied arts, and digital media technologies.',
    logo: digitalMediaLogo,
    logoAlt: 'MIDAS student organization logo',
    route: '/BSDMIA',
    accent: '#8050b8',
  },
  {
    code: 'BLIS',
    title: 'Library Information Science',
    description:
      'The Bachelor of Library and Information Science (BLIS) is a four-year program that prepares students for careers in information services.',
    logo: libraryScienceLogo,
    logoAlt: 'Library and Information Science student organization logo',
    route: '/BLIS',
    accent: '#55a9d1',
  },
]
</script>

<template>
  <section id="programs" class="programs-section" aria-label="Academic programs">
    <div class="program-grid">
      <article
        v-for="program in programs"
        :id="`program-${program.code.toLowerCase()}`"
        :key="program.code"
        class="program-card"
        :style="{ '--program-accent': program.accent }"
      >
        <div class="program-logo-wrap">
          <RouterLink
            :to="program.route"
            :aria-label="`Open ${program.title} program page`"
          >
            <img class="program-logo" :src="program.logo" :alt="program.logoAlt" />
          </RouterLink>
        </div>
        <div class="program-details">
          <p class="program-code">{{ program.code }}</p>
          <h2>{{ program.title }}</h2>
          <p class="program-description">{{ program.description }}</p>
          <RouterLink
            class="program-enter"
            :to="program.route"
            :aria-label="`Explore ${program.title} program`"
          >
            <span>Explore program</span>
            <span class="program-enter-arrow" aria-hidden="true">→</span>
          </RouterLink>
        </div>
      </article>
    </div>
  </section>
</template>

<style scoped>
.programs-section {
  display: grid;
  place-items: center;
  min-height: 470px;
  padding: 2rem;
  background: #f3f4f6;
  scroll-margin-top: 5rem;
}

.program-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  align-items: stretch;
  gap: 1.25rem;
  max-width: 1100px;
  margin: 0 auto;
}

.program-card {
  display: flex;
  flex-direction: column;
  min-width: 0;
  text-align: center;
  scroll-margin-top: 5rem;
  transition: transform 0.2s ease, filter 0.2s ease;
}

.program-card:hover {
  transform: translateY(-5px);
  filter: drop-shadow(0 10px 18px rgba(31, 41, 55, 0.12));
}

@media (prefers-reduced-motion: reduce) {
  .program-card {
    transition: none;
  }

  .program-card:hover {
    transform: none;
  }
}

.program-logo-wrap {
  display: grid;
  place-items: center;
  min-height: 132px;
  padding: 1rem;
  border: 1px solid #e5e7eb;
  border-bottom: 0;
  border-top: 4px solid var(--program-accent);
  border-radius: 12px 12px 0 0;
  background: #ffffff;
}

.program-logo {
  width: 88px;
  height: 88px;
  object-fit: contain;
}

.program-details {
  position: relative;
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: center;
  box-sizing: border-box;
  min-height: 260px;
  padding: 1.35rem 1.25rem 3.5rem;
  border: 1px solid #e5e7eb;
  border-top: 0;
  border-radius: 0 0 12px 12px;
  background: #ffffff;
  box-shadow: 0 5px 16px rgba(31, 41, 55, 0.08);
}

.program-code {
  margin: 0 0 0.35rem;
  color: var(--program-accent);
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.08em;
}

.program-details h2 {
  margin: 0.3rem 0 0.8rem;
  color: #243447;
  font-family: Georgia, 'Times New Roman', serif;
  font-size: 1.08rem;
  font-weight: 500;
  line-height: 1.25;
}

.program-description {
  margin: 0;
  color: #626d78;
  font-size: 0.78rem;
  line-height: 1.8;
}

.program-enter {
  position: absolute;
  left: 50%;
  bottom: 0.85rem;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.55rem 0.8rem;
  border: 1px solid var(--program-accent);
  border-radius: 999px;
  background: #ffffff;
  color: var(--program-accent);
  font-size: 0.72rem;
  font-weight: 700;
  white-space: nowrap;
  text-decoration: none;
  transform: translateX(-50%);
  transition: background-color 0.2s ease, color 0.2s ease, transform 0.2s ease;
}

.program-enter:hover,
.program-enter:focus-visible {
  background: var(--program-accent);
  color: #ffffff;
  transform: translate(-50%, -2px);
}

.program-enter-arrow {
  font-size: 1rem;
  line-height: 0.8;
}

@media (max-width: 900px) {
  .program-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    max-width: 680px;
    gap: 1.5rem 1rem;
  }
}

@media (max-width: 640px) {
  .programs-section {
    min-height: 440px;
  }
}

@media (max-width: 440px) {
  .programs-section {
    padding-inline: 1rem;
  }

  .program-grid {
    grid-template-columns: 1fr;
    max-width: 320px;
  }
}
</style>
