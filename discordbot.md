<section id="About">
  <h1 style="font-weight: bold">Discord Bot Project </h1>
  Language: Python
  <br>
  APIs: discord.py, smtplib, tempmail, replit, Twilio
  <br>
  Features:
  <br>
  <ul>
     - Reward "Cred" to members of the discord server
    <br>
     - "Cred" can be "cashed in" for rewards such as, "muting", "deafening" and "kicking" other members of the server
    <br>
     - Text alerts on voice channel join to enabled users
    <br>
     - Custom admin text alerts to enabled users
    <br>
     - Request and recieve emails through a temp email using the discord bot
    <br>
     - Utilizing Twilio to have the bot perform "wake up" calls to enabled users phones at user-specified times. (In Progress)
    <br>
  </ul>
  </section>
 <br>
 <section id="Examples">
    <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">Features</div>
        <span class="accordion-icon">+</span>
      </div>
       <div class="accordion-content">
         <a href="https://i.imgur.com/2Upd0Eq.png">Give Cred </a>
        <br>
         <a href="https://i.imgur.com/wiZjboM.png"> Rewards </a>
        <br>
         <a href="https://i.imgur.com/rMoUJUo.png">Text Alerts </a>
        <br>
         <a href="https://i.imgur.com/FsgC44d.png">Temp Email </a>
      </div>
    </div>
        <div class="accordion">
      <div class='accordion-header'>
        <div class="accordion-title">Video Demonstrations</div>
        <span class="accordion-icon">+</span>
      </div>
       <div class="accordion-content">
         <a href="https://youtu.be/tUliYlRtDt4">Give Cred Demonstration </a>
        <br>
         <a href="https://youtu.be/9JL36dAr3Zc"> Rewards Demonstration </a>
        <br>
         <a href="https://youtu.be/bETXtH8jMWs">Text Alerts Demonstration </a>
        <br>
         <a href="https://youtu.be/yliNWhPObvA">Temp Email Demonstration </a>
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
      

  
      
  
  
    


