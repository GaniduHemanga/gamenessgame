// Smooth page transition with exit animation
document.querySelectorAll('a').forEach(link => {
  link.addEventListener('click', function (e) {
    e.preventDefault();
    const href = this.getAttribute('href');

    // Add exit animation to title
    const title = document.querySelector('h1');
    title.classList.remove('animate__fadeInDown');
    title.classList.add('animate__fadeOutUp');

    // Fade out the whole body
    document.body.style.transition = 'opacity 0.5s';
    document.body.style.opacity = 0;

    setTimeout(() => {
      window.location.href = href;
    }, 500); // match this to animation duration
  });
});

window.addEventListener('DOMContentLoaded', () => {
  const title = document.getElementById('main-title');
  const subtitle = document.getElementById('subtitle');
  const buttons = document.getElementById('button-section');

  // Apply opening animations
  title.classList.add('animate__fadeInDown');
  subtitle.classList.add('animate__fadeInUp', 'animate__delay-1s');
  buttons.classList.add('animate__fadeInUp', 'animate__delay-2s');
});


// Scroll Reveal Animations
ScrollReveal().reveal('.buttons a', {
  delay: 400,
  distance: '20px',
  origin: 'bottom',
  duration: 800,
  interval: 200,
  reset: false
});

// Theme toggle
const themeToggle = document.getElementById('theme-toggle');
themeToggle.addEventListener('click', () => {
  document.body.classList.toggle('dark');
});
// Toggle menu
function toggleMenu() {
  document.getElementById('sidebar').classList.toggle('open');
}

// Move custom cursor
const cursor = document.getElementById('cursor');
document.addEventListener('mousemove', e => {
  cursor.style.left = (e.clientX - cursor.offsetWidth / 2) + 'px';
  cursor.style.top = (e.clientY - cursor.offsetHeight / 2) + 'px';
});
document.addEventListener('DOMContentLoaded', () => {
  // Title and subtitle entry
  document.getElementById('main-title').classList.add('animate__fadeInDown');
  document.getElementById('subtitle').classList.add('animate__fadeInUp', 'animate__delay-1s');

  // Button animations with increasing delays
  document.getElementById('btn1').classList.add('animate__fadeInUp', 'animate__delay-2s');
  document.getElementById('btn2').classList.add('animate__fadeInUp', 'animate__delay-3s');
  document.getElementById('btn3').classList.add('animate__fadeInUp', 'animate__delay-4s');
  document.getElementById('btn4').classList.add('animate__fadeInUp', 'animate__delay-5s');
});

