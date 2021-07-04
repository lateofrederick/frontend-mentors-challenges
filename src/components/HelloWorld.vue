<template>
  <div class="container">
    <div class="container__row">
      <div class="header">
        <img
          alt="image header"
          class="header__image"
          src="../assets/desktop/image-header.jpg"
        />
        <nav class="navbar">
          <div class="navbar-logo">sunnyside</div>
          <div class="navbar-items">
            <ul>
              <li><a href="">Contact</a></li>
              <li><a href="">Projects</a></li>
              <li><a href="">Services</a></li>
              <li><a href="">About</a></li>
            </ul>
          </div>
        </nav>
        <div class="creatives">
          <div class="creatives-label">
            <h1 class="creatives-label__text">WE ARE CREATIVES</h1>
          </div>
        </div>
        <div class="arrow">
          <img
            class="arrow-down"
            src="../assets/icon-arrow-down.svg"
            alt="arrow down"
          />
        </div>
      </div>
      <div class="transform photography">
        <div class="transform-message">
          <h2 class="transform-message__header">Transform your brand</h2>
          <p class="transform-message__content">
            We are a full-service creative agency specializing in helping brands
            grow fast.Engage your clients through compelling visuals that do
            most of the marketing for you.
          </p>
          <h4 class="transform-message-link">
            <a href="#" class="transform-message__link">LEARN MORE</a>
            <div class="underline"></div>
          </h4>
        </div>
        <img
          class="transform-image"
          src="../assets/desktop/image-transform.jpg"
          alt="image transform"
        />
      </div>
      <div class="standout">
        <img
          class="standout-image__image"
          src="../assets/desktop/image-stand-out.jpg"
          alt="image standout"
        />
        <div class="standout-message">
          <h2 class="standout-message__header">
            Stand out to the right audience
          </h2>
          <p class="standout-message__content">
            Using a collaborative formula of designers, reasearchers,
            photographers, videographers, and copywriters, we'll build and
            extend your brand in digital places.
          </p>
          <h4>
            <a href="#" class="standout-message__link">LEARN MORE</a>
            <div class="standout-underline"></div>
          </h4>
        </div>
      </div>
      <div class="graphic-design photography">
        <div class="graphic-design-image">
          <img
            class=""
            src="../assets/desktop/image-graphic-design.jpg"
            alt="image transform"
          />
          <div class="graphic-design-content">
            <h2 class="graphic-design-content__title">Graphic Design</h2>
            <p class="graphic-design-content__subtitle">
              Great design makes you memorable. We deliver artwork that makes
              underscores your brand message and captures potential clients'
              attention.
            </p>
          </div>
        </div>
        <div class="photography-image">
          <img
            class=""
            src="../assets/desktop/image-photography.jpg"
            alt="image standout"
          />
          <div class="photography-content">
            <h2 class="photography-content__title">Photography</h2>
            <p class="photography-content__subtitle">
              Increase your credibility by getting the most stunning,
              high-quality photos that improve your business image.
            </p>
          </div>
        </div>
      </div>
      <div class="testimonials">
        <h2 class="testimonials__heading">CLIENT TESTIMONIALS</h2>
        <div class="testimonials__client-testimonials">
          <div class="testimonial">
            <img
              class="testimonial__image"
              src="../assets/image-emily.jpg"
              alt="image emily"
            />
            <p class="testimonial__testimony-content">
              We put our trust in Sunnyside and they delivered, making sure our
              needs were met and deadlines were always hit.
            </p>
            <div class="details">
              <h4 class="details__name">Emily R.</h4>
              <p class="details__position">Marketing Director</p>
            </div>
          </div>
          <div class="testimonial">
            <img
              class="testimonial__image"
              src="../assets/image-thomas.jpg"
              alt="image thomas"
            />
            <p class="testimonial__testimony-content">
              Sunnyside's enthusiasm coupled with their keen interest in our
              brand's success made it a satisfying and enjoyable experience.
            </p>
            <div class="details">
              <h4 class="details__name">Thomas S.</h4>
              <p class="details__position">Chief Operating Officer</p>
            </div>
          </div>
          <div class="testimonial">
            <img
              class="testimonial__image"
              src="../assets/image-jennie.jpg"
              alt="image jennie"
            />
            <p class="testimonial__testimony-content">
              Incredible end result! Our sales increased over 42% when we worked
              with Sunnyside. Highly recommended!
            </p>
            <div class="details">
              <h4 class="details__name">Jennie F.</h4>
              <p class="details__position">Business Owner</p>
            </div>
          </div>
        </div>
      </div>
      <div class="cone milkbottles orange sugarcubes">
          <img
            class="milkbottles"
            src="../assets/desktop/image-gallery-milkbottles.jpg"
            alt="image milk-bottle"
          />
          <img
            class="orange"
            src="../assets/desktop/image-gallery-orange.jpg"
            alt="image orange"
          />
          <img
            class="cones"
            src="../assets/desktop/image-gallery-cone.jpg"
            alt="image cone"
          />
          <img
            class="sugarcubes"
            src="../assets/desktop/image-gallery-sugarcubes.jpg"
            alt="image sugarcubes"
          />
      </div>
      <div class="company-info">
        <img class="company-info-logo" src="../assets/logo.svg" alt="logo">
        <div class="about-services-projects">
          <a href="#" class="about">About</a>
          <a href="#" class="services">Services</a>
          <a href="#" class="projects">Projects</a>
        </div>
        <div class="social-media">
          <div class="facebook">
            <img src="../assets/icon-facebook.svg" alt="facebook icon" />
          </div>
          <div class="instagram">
            <img src="../assets/icon-instagram.svg" alt="instagram icon" />
          </div>
          <div class="twitter">
            <img src="../assets/icon-twitter.svg" alt="twitter icon" />
          </div>
          <div class="pinterest">
            <img src="../assets/icon-pinterest.svg" alt="pinterest icon" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  props: {},
})
export default class HelloWorld extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
* {
  margin: 0;
  padding: 0;
}

$rows: 7;

%grid__items2 {
  display: grid;
  grid-template-columns: auto auto;
}

%flex__items2 {
  display: flex;
}
%grid__items3 {
  display: grid;
  grid-template-columns: auto auto auto;
}

.container {
  overflow: hidden;
}
.header {
  display: grid;
  &__image {
    max-width: 100%;
  }
}

.creatives {
  position: absolute;
  top: 35%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.arrow {
  position: absolute;
  top: 65%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.creatives-label {
  margin-bottom: 25px;
  &__text {
    color: white;
    font-size: 58px;
  }
}

.testimonials {
  padding: 30vh 60px;
  &__heading {
    text-align: center;
    margin-bottom: 90px;
    color: lightgray;
  }
  &__client-testimonials {
    @extend %grid__items3;
    text-align: center;
    font-size: 22px;
  }
}
.transform,
.standout,
.photography {
  display: flex;
  flex-direction: row;
  max-width: 100%;
}

.cone {
  max-width: 100%;
  display: grid;
  grid-template-columns: auto auto auto auto;
}

// photography and graphic design images
.photography-image,
.graphic-design-image {
  width: 50%;
}

.photography-image {
  color: #19536b;
}

.graphic-design-image {
  color: #25564b;
}

.cones,
.sugarcubes,
.milkbottles,
.orange {
  width: 100%;
  margin: 0;
  padding: 0;
}

.transform-message,
.standout-message {
  padding: 20vh 7vw 0 6vw;
  text-align: left;
  &__header {
    font-size: 52px;
    font-weight: bold;
    margin-bottom: 34px;
  }
  &__content {
    font-size: 21px;
    margin-bottom: 44px;
    color: gray;
  }
}

.transform-message-link {
  font-size: 18px;
  color: black;
}

.underline {
  background-image: linear-gradient(to right, #fe7867, #fe7867 100%);
  background-position: 0 100%;
  background-repeat: repeat-x;
  background-size: 100% 8px;
  width: 28%;
  height: 8px;
  border-radius: 50px;
  background-origin: border-box;
  margin-top: -7px;
}

.standout-underline {
  background-image: linear-gradient(to right, #fe7867, #fe7867 100%);
  background-position: 0 100%;
  background-repeat: repeat-x;
  background-size: 100% 8px;
  width: 28%;
  height: 8px;
  border-radius: 50px;
  background-origin: border-box;
  margin-top: -7px;
}

.navbar {
  position: absolute;
  top: 8px;
  left: 10px;
  display: flex;
  justify-content: space-between;
  width: 95%;
}

.navbar-logo {
  float: left;
  color: #fff;
  padding: 1.5rem 0 1rem 1rem;
  font-size: xx-large;
  font-weight: bold;
}

.navbar li {
  float: right;
  text-decoration: none;
  text-align: center;
}

.navbar li a {
  display: inline-block;
  text-decoration: none;
  font-size: 18px;
  color: #fff;
  width: 90px;
  padding: 2rem 1.5rem 1rem 0;
  font-weight: bold;
}

li a:active {
  background-color: white;
  text-align: center;
  color: black;
  text-transform: uppercase;
  border-radius: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1rem 1rem;
  margin-top: 0.9rem;
}

ul {
  list-style-type: none;
  color: #fff;
}

.graphic-design-image, .photography-image {
  position: relative;
}

.graphic-design-content, .photography-content {
position: absolute;
bottom: 80px;
padding: 0rem 9.2045rem;
font-size: 18px;
text-align: center;
&__title {
margin-bottom: 30px;
font-family: 'Barlow';
}
}

.transform-message__link,
.standout-message__link {
  text-decoration: none;
  padding-left: 5px;
  color: black;
  font-size: 18px;
}

.testimonial {
  margin-right: 20px;
  font-weight: lighter;
  &__image {
    border-radius: 100px;
    width: 80px;
    height: 80px;
    margin-bottom: 50px;
  }
  &__testimony-content {
    margin-bottom: 60px;
    color: gray;
  }
}

.details {
  &__position {
    color: lightgray;
    font-size: 17px;
  }
}
.standout-image,
.transform-image {
  width: 50%;
  &__image {
    width: 50%;
  }
}
.company-info {
background-color: #63bfad;
margin: 0;
height: 300px;
padding: 0;
position: relative;
}

.company-info-logo {
position: absolute;
left: 44%;
bottom: 190px;
width: 150px;
height: 40px;
}

.about-services-projects {
position: absolute;
left: 40%;
width: 320px;
bottom: 130px;
display: flex;
font-size: 18px;
flex-direction: row;
justify-content: space-between;
}

.about, .services, .projects {
  text-decoration: none;
  color: #5a636c;
}

.social-media {
position: absolute;
left: 45%;
bottom: 35px;
width: 180px;
display: flex;
flex-direction: row;
justify-content: space-between;
}

</style>
