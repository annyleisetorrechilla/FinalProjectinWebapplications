<script setup>
import { computed, ref } from 'vue'
import ciscoLogo from '../assets/Partners/1024px-Cisco_academy_logo.svg_-300x300.png'
import acerLogo from '../assets/Partners/acer-300x300.jpg.jpeg'
import huaweiLogo from '../assets/Partners/huawei-academy-logo.jpg.jpeg'

const isExpanded = ref(false)

const partners = [
  { name: 'Oracle Academy', logoText: 'ORACLE', kind: 'oracle' },
  { name: 'Cisco Networking Academy', logo: ciscoLogo },
  { name: 'Acer Academy', logo: acerLogo },
  { name: 'Huawei ICT Academy', logo: huaweiLogo },
]

const visiblePartners = computed(() => (isExpanded.value ? partners : partners.slice(0, 2)))
</script>

<template>
  <section id="partnerships" class="partners-section">
    <header class="section-header">
      <p class="eyebrow">Connect</p>
      <h2>Our Partners and Memberships</h2>
      <p class="subtitle">Driving technology for education</p>
    </header>

    <div
      class="partners-grid"
      :class="{ 'partners-grid--expanded': isExpanded }"
      aria-label="Partners and memberships"
    >
      <div v-for="partner in visiblePartners" :key="partner.name" class="partner">
        <div class="partner-logo">
          <div
            v-if="partner.kind === 'oracle'"
            class="oracle-wordmark"
            role="img"
            :aria-label="partner.name"
          >
            <span>{{ partner.logoText }}</span>
            <small>Academy</small>
          </div>
          <img v-else :src="partner.logo" :alt="partner.name" />
        </div>
        <p class="partner-name">{{ partner.name }}</p>
      </div>
    </div>

    <button
      class="view-more"
      type="button"
      :aria-expanded="isExpanded"
      @click="isExpanded = !isExpanded"
    >
      {{ isExpanded ? 'View Less' : 'View More' }}
    </button>
  </section>
</template>

<style scoped>
.partners-section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 470px;
  padding: 1.5rem 1.5rem 3rem;
  background: #3E3C3B;
  color: #263f44;
  text-align: center;
  scroll-margin-top: 5rem;
}

.section-header {
  margin: 0 auto;
}

.eyebrow {
  margin: 0 0 0.45rem;
  color: #ffffff;
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
}

.section-header h2 {
  margin: 0;
  color: #ffffff;
  font-size: clamp(1.6rem, 3vw, 2rem);
  font-weight: 700;
  line-height: 1.2;
}

.subtitle {
  margin: 0.25rem 0 0;
  color: #ffffff;
  font-size: 0.78rem;
}

.partners-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  align-items: start;
  justify-items: center;
  gap: 2rem 1.5rem;
  width: min(100%, 520px);
  margin: 3rem auto 0;
}

.partners-grid--expanded {
  grid-template-columns: repeat(2, minmax(0, 1fr));
  width: min(100%, 520px);
}

.partner {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.85rem;
  width: 100%;
}

.partner-logo {
  display: grid;
  place-items: center;
  width: 100%;
  height: 140px;
}

.partner-logo img {
  display: block;
  width: 130px;
  height: 130px;
  object-fit: contain;
}

.partner-name {
  min-height: 2.5em;
  margin: 0;
  color: #ffffff;
  font-size: 0.85rem;
  line-height: 1.4;
  text-align: center;
}

.oracle-wordmark {
  display: flex;
  flex-direction: column;
  align-items: center;
  color: #e44335;
  line-height: 1;
}

.oracle-wordmark span {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.55rem;
  font-weight: 700;
  letter-spacing: -0.06em;
}

.oracle-wordmark small {
  margin-top: 0.2rem;
  color: #ffffff;
  font-size: 0.95rem;
}

.view-more {
  min-width: 88px;
  margin: 2rem auto 0;
  padding: 0.55rem 0.9rem;
  border: 0;
  border-radius: 2px;
  background: #a1a1a1;
  color: #172d30;
  font-size: 0.65rem;
  cursor: pointer;
  transition: background-color 0.2s ease, transform 0.2s ease;
}

.view-more:hover {
  background: #b8b8b8;
  transform: translateY(-1px);
}

.view-more:focus-visible {
  outline: 2px solid #24484e;
  outline-offset: 3px;
}

@media (max-width: 560px) {
  .partners-section {
    padding-inline: 1rem;
  }

  .partners-grid,
  .partners-grid--expanded {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    width: min(100%, 520px);
    gap: 1.4rem 1rem;
    margin: 2rem auto 0;
  }
}

@media (max-width: 640px) {
  .partners-section {
    min-height: 440px;
  }
}
</style>
