<h1> Shawn Brown </h1>
# Headshot (Photo)
# Contact Fields
# Job Title or Desired title
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
    background-color: #7393B3
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
          <div class="accordion-title"">Greater Altoona Career and Technology Center </div>
          <span class="accordion-icon">+</span>
        </div>
        <div class="accordion-content">
          Cisco Networking 2017
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
# Previous Job Experience
# Skills

