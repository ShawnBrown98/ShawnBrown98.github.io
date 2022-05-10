<h1> Shawn Brown </h1>
# Headshot (Photo)
# Contact Me
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
    <section id="Contact">
    </section>
# Job Title
<h1> Jr. Software Engineer </h1>
# Education
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
    <section id="education">
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
  <h1> Previous Job Experience </h1>
  <section id="Previous Job Experience">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">United States Army Reserve </div>
        <span class="accordion-icon">+</span>
      </div>
      <div class="accordion-content">
        22 June 2016 - 21 June 2022
      </div>
    </div>
    <section id="education">
      <div class="accordion">
        <div class='accordion-header'>
          <div class="accordion-title">Best Buy</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
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
        Discord Bot Project (Python)
        <br>
        Unity Games (C#)
        <br>
        Calculator (JavaScript)
        <br>
        Inches to CM/MM Converter (C++)
        <br>
        Seasons Changer (JavaScript)
      </div>
    </div>
    <section id="Skills">
      <div class="accordion">
        <div class='accordion-header'>
          <div class="accordion-title">Cybersecurity</div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
          Mount Aloysius College Cyber Defense Team
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
