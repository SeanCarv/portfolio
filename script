document.addEventListener('DOMContentLoaded', function () {
  const menuIcon = document.getElementById('menu-icon');
  const navMenu = document.getElementById('nav-menu');

  function toggleNavMenu() {
    if (window.innerWidth < 789) {
      if (navMenu.style.display === 'block' || navMenu.style.display === '') {
        navMenu.style.display = 'none';
      } else {
        navMenu.style.display = 'block';
      }
    } else {
      navMenu.style.display = 'block';
    }
  }

  // Add an event listener to your menuIcon to call the toggleNavMenu function
  menuIcon.addEventListener('click', toggleNavMenu);
});

toggleNavMenu():
window.addEventListener('resize', toggleNavMenu);
