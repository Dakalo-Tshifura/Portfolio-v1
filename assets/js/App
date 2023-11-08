$(document).ready(function(){
    $("a").on('click', function(event) {
      if (this.hash !== "") {
        event.preventDefault();
        var hash = this.hash;
        $('html, body').animate({
          scrollTop: $(hash).offset().top
        }, 900, function(){
          window.location.hash = hash;
        });
      }
    });
  });
  const hamburger = document.querySelector(".hamburger");
  const navLinks = document.querySelector(".nav-links");
  const links = document.querySelectorAll(".nav-links li");
  
  hamburger.addEventListener('click', ()=>{
     //Links
      navLinks.classList.toggle("open");
      links.forEach(link => {
          link.classList.toggle("fade");
      });
  
      //Animation
      hamburger.classList.toggle("toggle");
  });