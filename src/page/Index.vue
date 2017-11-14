<template>
  <div id="index">
    <section id="index1">
      <div class="section-1">
        <h1>Discover our services</h1>
        <div class="text-area">
          <h3>Here at Chanvre Quebec, our purpose is to popularize what we believe to be the greatest ecological solution. To do so, we have lauched <strong>rebrand</strong>; a new division that offers all the essentials to build a strong image around your hemp business.</h3>
        </div>
      </div>
    </section>
    <section>
      <div class="section-2">
        <div class="text-zone">
          <h2>Web development</h2>
          <p>Our web development services are high-end custom web apps. We develop a proper design that fits your need rather than the opposite. We truly focus on analytics to optimize your presence on the web.</p>
          <a href="mailto:allo@chanvrequebec.com">
            <button class="apply-now">talk with our team</button>
          </a>
        </div>
        <img class="image-zone" src="../assets/webdev-1.png" alt="macbook jechanvre.io web">
      </div>
    </section>
    <section>
      <div class="section-3">
        <img src="../assets/facebook-page.png" alt="facebook chanvre quebec">
        <div class="text-zone">
          <h2>Social Media</h2>
          <p>In today's world, business need to build and maintain a strong community around their brand. Social media plays a cenrtal role in that journey. From Instagram to Facebook, let us help you find the best strategy to suit your business profile.</p>
          <a href="mailto:allo@chanvrequebec.com">
            <button class="apply-now">talk with our team</button>
          </a>
        </div>
      </div>
    </section>
    <section>
      <div class="section-2">
        <div class="text-zone">
          <h2>Photos & Videos</h2>
          <p>Get your teams, services and products a nice look with services from experienced and creative photographers and videographers.</p>
          <a href="mailto:allo@chanvrequebec.com">
            <button class="apply-now">talk with our team</button>
          </a>
        </div>
        <iframe width="640" height="360" src="https://www.youtube.com/embed/5svVIY_DU20" frameborder="0" gesture="media" allowfullscreen></iframe>
      </div>
    </section>
    <section>
      <div class="section-3">
        <img src="../assets/branding.jpg" alt="chanvre quebec graine de chanvre">
        <div class="text-zone">
          <h2>Branding</h2>
          <p>Last but not least, we love creating brand identity. From color mockups and logos to packaging, we build branding guides adapted to your preferenced and market tendencies. This will give you the opportunity to create a harmony between your website, your social media and your products.</p>
          <a href="mailto:allo@chanvrequebec.com">
            <button class="apply-now">talk with our team</button>
          </a>
        </div>
      </div>
    </section>
    <section>
      <div class="section-1">
        <h2>Our special agents</h2>
        <div class="team">
          <div class="team-member">
            <img src="../assets/darko.jpg" alt="">
            <h4>Darko Popovic</h4>
            <p>Business strategy</p>
          </div>
          <div class="team-member">
            <img src="../assets/jeremie.jpg" alt="">
            <h4>Jérémie Aubut</h4>
            <p>Creative Leader</p>
          </div>
          <div class="team-member">
            <img src="../assets/jo.jpg" alt="">
            <h4>Jonathan Gagné</h4>
            <p>Smooth talker</p>
          </div>
          <div class="team-member">
            <img src="../assets/felix_chagnong.jpg" alt="">
            <h4>Félix Chagnon</h4>
            <p>Eagle Eye Photographer</p>
          </div>
        </div>
      </div>
    </section>
    <footer>
      <div class="footer-social">
        <img src="../assets/twitter-black.svg" alt="twitter logo">
        <img src="../assets/instagram-black.svg" alt="instagram logo">
      </div>
      <div class="footer-text">
        <h3>Start your image <a href="mailto:allo@chanvrequebec.com"><span class="yellow-here">here</span></a></h3>
      </div>
      <div class="footer-right">
        <div class="footer-line"></div>
        <p>© 2017 Chanvre Quebec <br>All rights reserved.</p>
        <p>Crafted with love <br />at Chanvre Quebec</p>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: 'index'
}
</script>
<style lang="sass" scoped>
@import '../assets/css/_main'

section
  height: 85vh
  display: grid
  grid-template: 5% 45% 45% 5% / 2% 48% 48% 2%
  img
    height: auto
    max-height: 100%
    width: auto
    max-width: 50vw
.section-1
  grid-area: 2/2/4/4
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column nowrap
  background: white
  padding: 10px 25px
  border-radius: 5px
.section-2
  grid-area: 2/2/4/4
  display: flex
  flex-flow: row nowrap
  justify-content: space-around
  align-items: center
  background: $light-grey
  padding: 25px 45px
  border-radius: 5px
.section-3
  grid-area: 2/2/4/4
  display: flex
  flex-flow: row nowrap
  justify-content: space-around
  padding: 25px 45px
  align-items: center
.text-zone
  display: flex
  flex-flow: column nowrap
  text-align: left
  max-width: 35%
.image-zone
  align-self: right
.text-area
  padding: 0 30%
.team
  display: flex
  flex-flow: row wrap
  justify-content: center
  align-items: center
  padding: 5%
.team-member
  display: flex
  flex-flow: column nowrap
  justify-content: center
  align-items: center
  align-content: center
  padding: 0 25px
  text-align: center
  max-width: 130px
  h4
    margin: 0
  p
    margin: 0
  img
    height: 100px
    width: 100px
    border-radius: 100%
    margin: 15px
.allo
  display: flex
  flex-flow: column nowrap
  height: 100vh
  justify-content: flex-end
  align-items: center
h1
  font-family: 'Abril Fatface', cursive
  color: $grey
  font-weight: 300
  font-size: 3.5rem
  letter-spacing: 2px
h2
  font-family: 'Abril Fatface', cursive
  font-size: 3rem
  font-weight: 300
  margin-bottom: 0
h3
  font-family: 'Varela Round', sans-serif
  line-height: 1.7rem
  color: black
p
  font-family: 'Varela Round', sans-serif
  line-height: 1.5rem
  color: $grey
button
  border: none
  align-self: center
  cursor: pointer
.apply-now
  width: 250px
  height: 50px
  background: $yellow
  color: white
  border-radius: 5px
  margin: auto
  opacity: 0.7
  &:hover
    opacity: 1
    transform: translateY(-1px)
footer
  display: grid
  grid-template: 20% 60% 20% / 4% 10% 72% 10% 4%
  margin: 30px
  padding: 35px
  height: 30vh
  background: $light-grey
  border-radius: 5px
.footer-logo
  grid-area: 1/2/2/3
  img
    height: 20px
.footer-social
  display: flex
  flex-flow: row wrap
  align-self: flex-start
  justify-content: center
  grid-area: 1/4/2/5
  img
    height: 15px
    padding: 10px 10px
.footer-text
  grid-area: 2/3/3/4
  font-family: 'Roboto-Bold', sans-serif
  font-size: 1.1rem
  color: $grey
  letter-spacing: 0
  text-align: center
  .yellow-here
    color: $yellow
    font-weight: 500
    cursor: pointer
    opacity: 0.7
    &:hover
      opacity: 1
  h3
    color: $grey
  a
    color: $grey
    text-decoration: none
    &:hover
      cursor: pointer
      color: black
.footer-right
  display: flex
  flex-flow: row wrap
  justify-content: space-between
  grid-area: 3/3/4/4
  margin-bottom: 15px
  p
    font-family: 'Roboto', sans-serif
    align-self: center
    font-size: 0.6rem
    color: $grey
.footer-line
  grid-area: 3/3/4/4
  width: 100%
  align-self: top
  margin-top: 15px
  border: 1px solid $grey
@media only screen and (max-width: 568px)
  section
    height: 100%
    img
      height: auto
      width: 90vw
  .section-3
    flex-flow: row wrap
    img
      order: 2
      margin-top: 25px
  .section-1
    flex-flow: column nowrap
    height: 100%
  .section-2
    flex-flow: row wrap
  .team
    height: 100%
  .team-member
    padding: 0
  .text-area
    padding: 0 5%
  .text-zone
    max-width: 100%
  footer
    height: 100%
  iframe
    margin-top: 25px
</style>
