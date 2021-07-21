# covid19
Reveal.on( 'slidechanged', event => {   // event.currentSlide, event.indexh, event.indexv   console.log(event.currentSlide);   document.querySelector('#slide-next').value = event.nextSlide; //nextSlide seems not exist though. } );
