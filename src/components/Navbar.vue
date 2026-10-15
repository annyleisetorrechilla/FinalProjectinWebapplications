<template>
  <header class="navbar-wrap">
    <div class="navbar">
      <a href="#hero" class="brand" aria-label="CCS home">
        <img src="@/assets/LOGO.png" alt="CCS" />
      </a>

      <nav class="nav-links" aria-label="Main navigation">
        <a class="active" href="#hero">Home</a>
        <a href="#programs">Academic Programs</a>
        <a href="#partnerships">Partnerships</a>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.navbar-wrap {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  z-index: 20;
  background: transparent;
}

.navbar {
  max-width: 790px;
  margin: 0 auto;
  padding: 0.45rem 0.5rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.5rem;
}

.brand {
  display: block;
  flex: 0 0 auto;
}

.brand img {
  width: 38px;
  height: 38px;
  object-fit: contain;
}

.nav-links {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  gap: clamp(0.65rem, 1.5vw, 1.4rem);
}

.nav-links a {
  text-decoration: none;
  color: #a1a1a1;
  font-size: 0.72rem;
  font-weight: 600;
  white-space: nowrap;
  transition: color 0.2s ease;
}

.nav-links a:hover,
.nav-links a:focus-visible,
.nav-links a.active {
  color: #ffffff;
}

@media (max-width: 640px) {
  .navbar {
    max-width: 100%;
    padding: 0.5rem 1rem;
    align-items: center;
  }

  .nav-links {
    gap: 0.75rem;
    overflow-x: auto;
  }

  .nav-links a {
    font-size: 0.65rem;
  }
}
</style>
