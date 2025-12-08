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

.nav-dropdown-m
