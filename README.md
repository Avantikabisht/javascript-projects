# NO Framework Please - Javascript Only :computer:

This repo is dedicated to vanilla JavaScript projects and code snippets. If you are looking to pratice, or just want to start then this repo is for you. The idea is to practise with vanilla JavaScript. 

# Tech Stack
- HTML5
- CSS
- JavaScript

# Projects Ideas

 1. Tip calculator  :white_check_mark:
 2. Cost split  :white_check_mark:
 3. Calculator 
 4. Form validator 
 5. Color picker :white_check_mark:
 6. Flyout navigation
 7. Hover effect :white_check_mark:
 8. Slide-in/out on click - Sliding is done , animation is left
 9. Popup
 10. Tootlip - done by 2 solution, CSS and JS. However, would like to add
 11. JS animations.
 12. To-do list
 13. Quiz
 14. Astrology predict
 15. Color scale generator
 16. Create components
 17. E-commerce - color change of product
 18. Chat
 19. Conversion of units
 20. gif search
 21. Tweet search
 22. Random image
 23. Quote generator
 24. Sliders
 25. Tabs/Accordion
 26. Progress bar
 27. Word count
 28. Search for word in a page

# Contribution
Repo is open for the PRs

# Reach Me
You can reach me at nsharma215@gmail.com or follow me at [Twitter](https://twitter.com/hellonehha)





<!-- Display the countdown timer in an element -->
<p id="CountDownTimer"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Jan 5, 2021 15:37:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="CountDownTimer"
  document.getElementById("CountDownTimer").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

