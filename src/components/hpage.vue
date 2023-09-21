<script setup>
import {ref} from 'vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
   <main id="main">

<!-- ======= About Section ======= -->
<section id="about" class="about">
  <div class="container">

    <div class="row no-gutters">
      <div class="content col-xl-5 d-flex align-items-stretch" data-aos="fade-up">
        <div class="content">
          <h3>Let me introduce you to Football</h3>
          <p>
Football, known as soccer in some regions, is a popular team sport played on a rectangular field with the objective of scoring goals by getting the ball into the opponent's net while preventing them from doing the same. It boasts a rich history, with origins dating back to ancient civilizations, and has evolved into a global phenomenon, captivating millions of fans worldwide. With its simple yet dynamic gameplay, a team of 11 players on each side, and a focus on skills, teamwork, and strategy, football stands as one of the most cherished and widely followed sports on the planet, fostering a sense of unity and passion among its enthusiasts.
          </p>
          <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjk1dnoo7eBAxVFVt4KHcHwDpsQFnoECDkQAQ&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FFootball&usg=AOvVaw20BeW_nFSVhP7255ZD3Dd_&opi=89978449" class="about-btn">Learn more  <i class="bx bx-chevron-right"></i></a>
        </div>
      </div>
      <div class="col-xl-7 d-flex align-items-stretch">
        <div class="icon-boxes d-flex flex-column justify-content-center">
          <div class="row">
            <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="100">
              <i class="bx bx-receipt"></i>
              <h4>Objective and Gameplay:</h4>
              <p>Football's primary objective is to score goals. Teams of 11 players each aim to get the ball into the opponent's goal while defending their own. The game emphasizes passing, dribbling, and teamwork to advance the ball up the field and create scoring opportunities.</p>
            </div>
            <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="200">
              <i class="bx bx-cube-alt"></i>
              <h4>Rules and Fouls:</h4>
              <p>Football is governed by a set of rules established by FIFA. Players are not allowed to use their hands or arms (except for goalkeepers within their penalty area). Fouls, such as tripping or pushing opponents, result in free kicks or penalty kicks for the opposing team, depending on the severity and location of the foul.</p>
            </div>
            <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="300">
              <i class="bx bx-images"></i>
              <h4>International Significance:</h4>
              <p> Football is more than just a sport; it's a global cultural phenomenon. Major tournaments like the FIFA World Cup attract enormous audiences and showcase the world's best talent. Countries and fans passionately support their national teams, and the sport fosters a sense of unity and identity</p>
            </div>
            <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="400">
              <i class="bx bx-shield"></i>
              <h4>Skills and Strategy:</h4>
              <p>Success in football requires a combination of skills, including ball control, passing accuracy, speed, and defensive prowess. Coaches develop strategic plans for their teams, and players must adapt to various styles of play, from possession-based to counterattacking football, to succeed at the highest levels.</p>
            </div>
          </div>
        </div><!-- End .content-->
      </div>
    </div>

  </div>
</section><!-- End About -->

<!-- ======= Position Section ======= -->
<section id="Position" class="services">
  <div class="container">

    <div class="section-title" data-aos="fade-in" data-aos-delay="100">
      <h2>Wanna Start?</h2>
      <p style="text-align:left"  >-->Lets start with positions</p>
      <p> Positions in football serve a fundamental purpose, essential to the game's strategy and dynamics. Each position has a distinct role and responsibility, contributing to the team's overall success. This division of roles allows players to specialize in specific aspects of the game, such as scoring goals, defending the goal, controlling the midfield, or orchestrating attacks. The diverse positions create a structured and balanced team, fostering teamwork, tactical versatility, and the ability to adapt to different situations during a match. Understanding why positions exist in football provides insight into the intricacies of the sport and how individual skills combine to form a cohesive and competitive team.</p>
    </div>

    <div class="row">
      <div class="col-md-6 col-lg-3 d-flex align-items-stretch mb-5 mb-lg-0">
        <div class="icon-box" data-aos="fade-up">
          <div class="icon"><i class="bx bxl-dribbble"></i></div>
          <h4 class="title"><a href="">Goalkeeper (GK):</a></h4>
          <p class="description">Defends the goal and initiates plays.</p>
        </div>
      </div>

      <div class="col-md-6 col-lg-3 d-flex align-items-stretch mb-5 mb-lg-0">
        <div class="icon-box" data-aos="fade-up" data-aos-delay="100">
          <div class="icon"><i class="bx bx-file"></i></div>
          <h4 class="title"><a href="">Defenders (CB, RB, LB):</a></h4>
          <p class="description">Guard against attacks and may join the offense</p>
        </div>
      </div>

      <div class="col-md-6 col-lg-3 d-flex align-items-stretch mb-5 mb-lg-0">
        <div class="icon-box" data-aos="fade-up" data-aos-delay="200">
          <div class="icon"><i class="bx bx-tachometer"></i></div>
          <h4 class="title"><a href="">Midfielders (CDM, CM, CAM, RM, LM):</a></h4>
          <p class="description">Control the game, create chances, and defend.</p>
        </div>
      </div>

      <div class="col-md-6 col-lg-3 d-flex align-items-stretch mb-5 mb-lg-0">
        <div class="icon-box" data-aos="fade-up" data-aos-delay="300">
          <div class="icon"><i class="bx bx-world"></i></div>
          <h4 class="title"><a href="">Forwards (CF, ST, SS): </a></h4>
          <p class="description">Score goals and assist in attacking plays.</p>
      </div>
    </div>
    </div>

  </div>
</section><!-- End Services Section -->

<!-- ======= Counts Section ======= -->
<!--<section id="counts" class="counts  section-bg">
  <div class="container">

    <div class="row no-gutters">

      <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch">
        <div class="count-box">
          <i class="bi bi-emoji-smile"></i>
          <span data-purecounter-start="0" data-purecounter-end="232" data-purecounter-duration="1" class="purecounter"></span>
          <p><strong>Happy Clients</strong> consequuntur quae</p>
        </div>
      </div>

      <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch">
        <div class="count-box">
          <i class="bi bi-journal-richtext"></i>
          <span data-purecounter-start="0" data-purecounter-end="521" data-purecounter-duration="1" class="purecounter"></span>
          <p><strong>Projects</strong> adipisci atque cum quia aut</p>
        </div>
      </div>

      <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch">
        <div class="count-box">
          <i class="bi bi-headset"></i>
          <span data-purecounter-start="0" data-purecounter-end="1463" data-purecounter-duration="1" class="purecounter"></span>
          <p><strong>Hours Of Support</strong> aut commodi quaerat</p>
        </div>
      </div>

      <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch">
        <div class="count-box">
          <i class="bi bi-people"></i>
          <span data-purecounter-start="0" data-purecounter-end="15" data-purecounter-duration="1" class="purecounter"></span>
          <p><strong>Hard Workers</strong> rerum asperiores dolor</p>
        </div>
      </div>

    </div>

  </div>
</section> End Counts Section -->

<!-- ======= Cta Section ======= -->
<section id="cta" class="cta">
  <div class="container" data-aos="zoom-in">

    <div class="text-center">
      <h3></h3>
      <p style="font-weight: bold; font-family: monospace;">"From the backyard pick-up games to the grand stadiums, football teaches us the values of teamwork, perseverance, and the pursuit of victory against all odds."</p>
      <a class="cta-btn" href="#">Call To Action</a>
    </div>

  </div>
</section><!-- End Cta Section -->

<!-- ======= Portfolio Section ======= -->
<section id="gallery" class="portfolio">
  <div class="container">

    <div class="section-title" data-aos="fade-in" data-aos-delay="100">
      <h2>Some famous profiles</h2>
      <p></p>
    </div>

    <div class="row" data-aos="fade-in">
      <div class="col-lg-12 d-flex justify-content-center">
        <ul id="portfolio-flters">
          <li data-filter="*" class="filter-active">All</li>
          <!---<li data-filter=".filter-app">App</li>
          <li data-filter=".filter-card">Card</li>
          <li data-filter=".filter-web">Web</li>-->
        </ul>
      </div>
    </div>

    <div class="row portfolio-container" data-aos="fade-up">

      <div class="col-lg-4 col-md-6 portfolio-item filter-app">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-1.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-1.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="App 1"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-web">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-2.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-2.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Web 3"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-app">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-3.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-3.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="App 2"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-card">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-4.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-4.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Card 2"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-web">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-5.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-5.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Web 2"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-app">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-6.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-6.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="App 3"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-card">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-7.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-7.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Card 1"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-card">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-8.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-8.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Card 3"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

      <div class="col-lg-4 col-md-6 portfolio-item filter-web">
        <div class="portfolio-wrap">
          <img src="src/assets/img/portfolio/portfolio-9.jpg" class="img-fluid" alt="">
          <div class="portfolio-links">
            <a href="src/assets/img/portfolio/portfolio-9.jpg" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Web 3"><i class="bx bx-plus"></i></a>
            <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
          </div>
        </div>
      </div>

    </div>

  </div>
</section><!-- End Portfolio Section -->



<!-- ======= Team Section ======= -->
<section id="team" class="team">
  <div class="container">

    <div class="section-title" data-aos="fade-in" data-aos-delay="100">
      <h2>Team</h2>
      <p>Me,Myself and I</p>
    </div>

      <div class="col-lg-4 col-md-6">
            <div class="member" data-aos="fade-up" data-aos-delay="150"  style="text-align: center;">
              <div class="pic"><img src="src/assets/img/team/team.jpg" class="img-fluid" alt="" style="display: block; margin: 0 auto;"></div>
              <div class="member-info">
                <h4>Harshit</h4>
                <span>Student</span>
              
              </div>
            </div>
     </div>
  </div>
  
</section><!-- End Team Section -->

</main><!-- End #main -->
</template>

<style scoped>
 
</style>
