---
layout: default
---

# Welcome to the Marianski Group Website

---

<div class="slider">
 <div class="slides">
  
  <input type="radio" name="radio-btn" id="radio1">
  <input type="radio" name="radio-btn" id="radio2">
  <input type="radio" name="radio-btn" id="radio3">
  <input type="radio" name="radio-btn" id="radio4">

  <div class="slide first">
   <img src="/assets/img/dof.png" alt="" width=750px>
  </div>
  <div class="slide">
   <img src="/assets/img/comp_methods.png" alt="" width=750px>
  </div>
  <div class="slide">
   <img src="/assets/img/Viruses.png" alt="" width=750px>
  </div>
  <div class="slide">
   <img src="/assets/img/flexibleSCR.jpg" alt="" width=750px>
  </div>

  <div class="navigation-auto">
   <div class="auto-btn1"></div>
   <div class="auto-btn2"></div>
   <div class="auto-btn3"></div>
   <div class="auto-btn4"></div>
  </div>

 </div>

 <div class="navigation-manual">
  <label for="radio1" class="manual-btn"></label>
  <label for="radio2" class="manual-btn"></label>
  <label for="radio3" class="manual-btn"></label>
  <label for="radio4" class="manual-btn"></label>
 </div>

</div>

<script type="text/javascript">
var counter = 1;
setInterval(function(){
 document.getElementById('radio' + counter).checked = true;
 counter++;
 if(counter > 4){
  counter = 1;
 }
}, 5000);

</script>

<br>

<p>
Here at the Marianski Lab, we use methods of computational chemistry to investigate carbohydrates. Being alike building blocks with complex assembly rules, carbohydrates offer a virtually limitless sequential/structural space for the discovery of biocompatible and biodegradable materials with desirable properties. Being able to understand and synthetically access this 'sugar code' would open new avenues in medicine, therapeutics, chemical sensing, and materials science.
</p>
