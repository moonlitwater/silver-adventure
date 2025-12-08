---
layout: default
---

<style>
/* ------------------------------------------------------
   Silver Adventure — Clean White x Midnight Blue Theme
   Navigation on Right – Medium-style aesthetic
-------------------------------------------------------*/

/* Global layout */
body {
  font-family: "Georgia", "Times New Roman", serif;
  background: #ffffff;
  color: #111827;
  max-width: 720px;
  margin: 0 auto;
  padding: 2rem 1.5rem;
  line-height: 1.7;
}

/* Title */
.site-title,
.site-title a {
  font-family: Georgia, serif;
  font-size: 2.6rem;
  font-weight: 600;
  color: #1f2933;
  text-decoration: none;
}

/* Midnight blue links */
a {
  color: #1f3a60;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

/* ------------------------------------------------------
   NAVIGATION BAR — RIGHT ALIGNED
-------------------------------------------------------*/
.nav-wrapper {
  display: flex;
  justify-content: flex-end;   /* Move menu to right */
  align-items: center;
  margin-top: 1.4rem;
  margin-bottom: 1.4rem;
}

.nav-menu {
  display: flex;
  gap: 1.6rem;
  align-items: center;
}

.nav-menu > a {
  font-family: "Inter", sans-serif;
  font-size: 0.92rem;
  font-weight: 500;
  color: #1f3a60;
}

/* Dropdown */
.nav-dropdown {
  position: relative;
  font-family: "Inter", sans-serif;
  font-size: 0.92rem;
  cursor: pointer;
}

.nav-dropdown-label {
  color: #1f3a60;
  font-weight: 500;
}

.nav-dropdown-menu {
  position: absolute;
  top: 1.6rem;
  right: 0;
  display: none;
  flex-direction: column;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  box-shadow: 0 8px 18px rgba(0,0,0,0.08);
  padding: 0.6rem 0.9rem;
  min-width: 160px;
  z-index: 10;
}

.nav-dropdown-menu a {
  font-size: 0.88rem;
  margin: 0.22rem 0;
}

.nav-dropdown:hover .nav-dropdown-menu {
  display: flex;
}

/* Hide GitHub footer & project link */
footer,
p > a[href*="moonlitwater/silver-adventure"] {
  display: none !important;
}
</style>

<div class="nav-wrapper">
  <nav class="nav-menu">
    <a href="/silver-adventure/">Home</a>
    <a href="/silver-adventure/about/">About Me</a>
    <a href="/silver-adventure/reach/">Reach Me</a>

    <div class="nav-dropdown">
      <span class="nav-dropdown-label">Notebook ▾</span>
      <div class="nav-dropdown-menu">
        <a href="/silver-adventure/writings/">Writings</a>
        <a href="/silver-adventure/reflections/">Reflections</a>
        <a href="/silver-adventure/stories/">Stories</a>
        <a href="/silver-adventure/language/">Language Notes</a>
      </div>
    </div>
  </nav>
</div>

---

Welcome to this small, calm corner of this digital universe —  
where I write, reflect, and sometimes tell a story. 🌙
