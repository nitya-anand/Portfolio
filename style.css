* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  background: #07040b;
  color: white;
  font-family: Arial, sans-serif;
  overflow-x: hidden;
}

body::before {
  content: "";
  position: fixed;
  inset: 0;
  background:
    radial-gradient(circle at 20% 20%, rgba(255, 129, 215, 0.18), transparent 28%),
    radial-gradient(circle at 80% 40%, rgba(95, 221, 255, 0.16), transparent 30%),
    radial-gradient(circle at 50% 90%, rgba(180, 112, 255, 0.16), transparent 32%);
  pointer-events: none;
  z-index: -3;
}

.liquid {
  position: fixed;
  border-radius: 50%;
  filter: blur(50px);
  opacity: 0.75;
  z-index: -2;
  mix-blend-mode: screen;
}

.liquid-one {
  width: 480px;
  height: 480px;
  background: linear-gradient(135deg, #ff6ec7, #7c5cff);
  top: 12%;
  right: 8%;
  animation: morphOne 9s ease-in-out infinite;
}

.liquid-two {
  width: 420px;
  height: 420px;
  background: linear-gradient(135deg, #00d4ff, #b46cff);
  bottom: 5%;
  left: 5%;
  animation: morphTwo 11s ease-in-out infinite;
}

@keyframes morphOne {
  0%, 100% {
    transform: translate(0, 0) scale(1);
    border-radius: 45% 55% 60% 40%;
  }
  50% {
    transform: translate(-40px, 35px) scale(1.12);
    border-radius: 60% 40% 45% 55%;
  }
}

@keyframes morphTwo {
  0%, 100% {
    transform: translate(0, 0) scale(1);
    border-radius: 55% 45% 40% 60%;
  }
  50% {
    transform: translate(45px, -30px) scale(1.1);
    border-radius: 40% 60% 55% 45%;
  }
}

.bubbles::before,
.bubbles::after {
  content: "";
  position: fixed;
  width: 14px;
  height: 14px;
  border-radius: 50%;
  background: rgba(255,255,255,0.6);
  box-shadow:
    120px 500px rgba(255,255,255,0.18),
    300px 650px rgba(255,255,255,0.15),
    650px 420px rgba(255,255,255,0.2),
    900px 700px rgba(255,255,255,0.16),
    1150px 520px rgba(255,255,255,0.18);
  animation: bubbleRise 9s linear infinite;
  z-index: -1;
}

.bubbles::after {
  width: 9px;
  height: 9px;
  animation-duration: 13s;
  animation-delay: -4s;
  opacity: 0.7;
}

@keyframes bubbleRise {
  from {
    transform: translateY(120px);
  }
  to {
    transform: translateY(-900px);
  }
}

nav {
  position: fixed;
  top: 0;
  width: 100%;
  padding: 28px 55px;
  z-index: 20;
  display: flex;
  justify-content: space-between;
  align-items: center;
  backdrop-filter: blur(18px);
  border-bottom: 1px solid rgba(255,255,255,0.08);
}

nav p {
  margin: 0;
  font-weight: bold;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 28px;
  opacity: 0.72;
  transition: 0.3s;
}

nav a:hover {
  opacity: 1;
}

.hero {
  min-height: 100vh;
  padding: 140px 55px 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.eyebrow {
  color: #f5b7ff;
  text-transform: uppercase;
  letter-spacing: 3px;
  font-size: 13px;
}

.hero h1 {
  font-size: clamp(72px, 12vw, 170px);
  line-height: 0.88;
  letter-spacing: -8px;
  margin: 22px 0;
  max-width: 1000px;
}

.intro {
  max-width: 720px;
  color: #e6d8ec;
  font-size: 24px;
  line-height: 1.45;
}

.section {
  min-height: 85vh;
  padding: 115px 55px;
  border-top: 1px solid rgba(255,255,255,0.12);
}

.section h2 {
  max-width: 1050px;
  font-size: clamp(42px, 7vw, 96px);
  line-height: 1;
  letter-spacing: -4px;
}

.reaction-grid {
  margin-top: 60px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
}

.reaction-card {
  position: relative;
  min-height: 330px;
  padding: 30px;
  border-radius: 34px;
  overflow: hidden;
  border: 1px solid rgba(255,255,255,0.18);
  background: rgba(255,255,255,0.07);
  backdrop-filter: blur(16px);
  transition: 0.35s;
}

.reaction-card::before {
  content: "";
  position: absolute;
  inset: -80px;
  background: radial-gradient(circle at var(--x, 50%) var(--y, 50%), rgba(255,255,255,0.28), transparent 24%);
  opacity: 0;
  transition: opacity 0.35s;
}

.reaction-card:hover {
  transform: translateY(-12px) scale(1.01);
  border-color: rgba(255,255,255,0.42);
}

.reaction-card:hover::before {
  opacity: 1;
}

.reaction-card span,
.reaction-card h3,
.reaction-card p {
  position: relative;
  z-index: 2;
}

.reaction-card span {
  color: #f5b7ff;
}

.reaction-card h3 {
  font-size: 32px;
  margin-top: 80px;
  letter-spacing: -1px;
}

.reaction-card p {
  color: #e6d8ec;
  font-size: 18px;
  line-height: 1.5;
}

.reveal {
  opacity: 0;
  transform: translateY(50px) scale(0.98);
  filter: blur(8px);
  transition: 0.9s ease;
}

.reveal.active {
  opacity: 1;
  transform: translateY(0) scale(1);
  filter: blur(0);
}

@media (max-width: 850px) {
  nav {
    padding: 22px;
  }

  nav div {
    display: none;
  }

  .hero,
  .section {
    padding-left: 25px;
    padding-right: 25px;
  }

  .reaction-grid {
    grid-template-columns: 1fr;
  }

  .hero h1 {
    letter-spacing: -4px;
  }
}
