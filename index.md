
<h1> Shawn Brown </h1>
<strong><h1><a href="operance.github.io">MY NEW PORTFOLTIO WEBSITE IS LOCATED AT OPERANCE.GITHUB.IO</strong></h1></a>
  <section id="About Me">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">About Me</div>
        <span class="accordion-icon">+</span>
      </div>
      <div class="accordion-content">
        I have always had a passion for programming, beginning when I first went to Codecademy at 14. The purpose of this portfolio website is to showcase the various projects I have been involved with/or created myself! My desired is to become a Junior Software Engineer!
      </div>
    </div>
  </section>
  
  <h1> Contact Me </h1>
  <section id="Contact">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">Email</div>
        <span class="accordion-icon">+</span>
      </div>
      <div class="accordion-content">
        stbrown98@gmail.com
      </div>
    </div>
      <div class="accordion">
        <div class='accordion-header'>
          <div class="accordion-title">Github</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
          <a href="https://github.com/Operance">My personal Github </a>
          <br>
          <a href="https://github.com/ShawnBrown98">My school Github </a>
        </div>
      </div>
  </section>
        
<style>
  .accordion{
    max-width: 500px;
    border: 1px solid #000;
  }
  .accordion-header {
    display: flex;
    padding: 16px;
    cursor: pointer;
    background-color: #F2F2F2
  }
  .accordion-icon {
    width: 16px
    color: #C00
  }
  .accordion-content {
    padding: 16px;

  }
  .accordion-title {
    flex: 1;
  }
  .accordion-content {
    display: none;
  }
</style>
  
  <h1> Education </h1>
  <section id="education">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">Mount Aloysius College </div>
        <span class="accordion-icon">+</span>
      </div>
      <div class="accordion-content">
        Bachelor of Science: Information Technology 2023
      </div>
    </div>
      <div class="accordion">
        <div class='accordion-header'>
          <div class="accordion-title">Greater Altoona Career and Technology Center </div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
          Cisco Networking 2017
        </div>
      </div>
    </section>
  
  <h1> Previous Job Experience </h1>
  <section id="Previous Job Experience">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">United States Army Reserve </div>
        <span class="accordion-icon">+</span>
      </div>
      <div class="accordion-content">
        Combat Engineer
        <br>
        22 June 2016 - 21 June 2022
        <br>
      </div>
    </div>
      <div class="accordion">
        <div class='accordion-header'>
          <div class="accordion-title">Best Buy</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
          Computing Sales Advisor
          <br>
          05 October 2020 - 30 April 2021
        </div>
      </div>
    </section>
    
  <h1> Skills </h1>
  <section id="Skills">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">Software Development</div>
        <span class="accordion-icon">+</span>
      </div>
      <div class="accordion-content">
        <a href="https://shawnbrown98.github.io/discordbot"> Discord Bot Project (Python)</a>
        <br>
        <a href="https://shawnbrown98.github.io/PortfolioBuild/index.html">Unity Game (C#) (In Progress)</a>
        <br>
        <a href="https://shawnbrown98.github.io/calculator.html">Calculator (JavaScript) </a>
        <br>
        <a href="https://replit.com/@operance/Playing-around-with-C#main.cpp">Basic inches to CM/MM Converter (C++) </a>
        <br>
        <a href="https://github.com/Operance/NPL/tree/master/Project%20NPL/Assets/Scripts"> Former Unity Game Project (JavaScript) </a>
      </div>
    </div>
      <div class="accordion">
        <div class='accordion-header'>
          <div class="accordion-title">Cybersecurity</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
          Mount Aloysius College Cyber Defense Team (2022-Present)
        </div>
      </div>
    </section>

<script>
const accordionHeaders = document.getElementsByClassName('accordion-header');
const accordionContents = document.getElementsByClassName('accordion-content');
const accordionIcons = document.getElementsByClassName('accordion-icon');

for(let i=0; i < accordionHeaders.length; i++){
  accordionHeaders[i].addEventListener('click', () => {
    accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
    accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '-' : '+';

  })
}
</script>
