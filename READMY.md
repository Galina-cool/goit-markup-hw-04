/* common */

.container {
  max-width: 1158px;
  padding: 0 15px;
  margin: 0 auto;
}

/* header */

.page-header {
  border-bottom: 1px solid #e7e9fc;
}

.header-container {
  display: flex;
  align-items: center;
}

.header-nav {
  display: flex;
  align-items: center;
}

.logo {
  font-family: 'Raleway', sans-serif;
  font-weight: 700;
  font-size: 18px;
  line-height: 1.17;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: #4d5ae5;
}

.header-logo {
  padding: 24px 0;
  margin-right: 76px;
}

.header-logo .logo-part {
  color: #2e2f42;
}

.footer-logo .logo-part {
  color: #f4f4fd;
}

.nav-list {
  display: flex;
  align-items: center;
  gap: 40px;
}

.nav-link {
  display: block;
  padding: 24px 0;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.5;
  letter-spacing: 0.02em;
  color: #2e2f42;
}

.contacts {
  font-style: normal;
  margin-left: auto;
}

.contacts-list {
  display: flex;
  align-items: center;
  gap: 40px;
}

.contacts-link {
  display: block;
  padding: 24px 0;
  font-size: 16px;
  line-height: 1.5;
  letter-spacing: 0.02em;
  color: #434455;
}

.nav-link:hover,
.nav-link:focus,
.contacts-link:hover,
.contacts-link:focus {
  color: #404bbf;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  padding: 0;
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}

display:flex;
flex-wrap:wrap;
gap:48px 24px; 
}
.portfolio-contents{ 
flex-basis:calc((100% - 2 * 24px) / 3); 