<template>
  <div class="view-wrap">
    <div class="view-content">
      <section id="hero" class="standard-hero text-center">
        <div class="section-inner">
          <p class="upper">Emily Krause</p>
          <h1>Hi there! I'm a talented beautiful girl with a cool website. Why don't you take some time and explore it!</h1>
        </div>
      </section>
      <section id="full-width-img">
        <img src="./images/portrait.jpg">
      </section>
      <section>
        <div class="section-inner experiences">
          <div class="container experience">
            <div class="row">
              <div class="col-xs-12 col-sm-3">
                <p class="upper label">About Me</p>
              </div>
              <div class="col-xs-12 col-sm-9">
                <p class="large">As a Sunflower State native, I have a deep love for Kansians and their neighborhoods. I approach both life and work with sincerity, honesty, and compassion. To me, there is nothing more rewarding than seeing a client fall in love with his or her new home.</p>
              </div>
            </div>
          </div>
          <div class="container experience">
            <div class="row">
              <div class="col-xs-12 col-sm-3">
                <p class="upper label">Experience</p>
              </div>
              <div class="col-xs-12 col-sm-9">
                <p class="large">For the past ten years, I have been helping people rent, buy, and sell homes. With a background in economics and communications, I have a thorough understanding of the real estate market and know what it takes to champion a client’s needs.</p>
                <p class="large">As a Sunflower State native, I have a deep love for Kansians and their neighborhoods. I approach both life and work with sincerity, honesty, and compassion. To me, there is nothing more rewarding than seeing a client fall in love with his or her new home.</p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="grid" class="bg-dark">
        <div class="section-inner">
          <div class="container">
            <div class="row">
              <a href="" class="col col-6">
                <div class="col-inner">
                  <p class="large">Explore</p>
                  <img src="./images/img-1.png">
                </div>
              </a>
              <a href="" class="col col-6">
                <div class="col-inner">
                  <p class="large">Fly</p>
                  <img src="./images/img-2.png">
                </div>
              </a>
              <a href="" class="col col-6">
                <div class="col-inner">
                  <p class="large">Travel</p>
                  <img src="./images/img-3.png">
                </div>
              </a>
              <a href="" class="col col-6">
                <div class="col-inner">
                  <p class="large">Experiment</p>
                  <img src="./images/img-4.png">
                </div>
              </a>
            </div>
          </div>
        </div>
      </section>
      <section>
        <div class="section-inner">
          <div class="text-center">
            <div>
              <a class="h4" href="mailto:emilyruthkrause@gmail.com">emilyruthkrause@gmail.com</a>
            </div>
            <div class="icons">
              <a href="https://www.twitter.com/emikrause" class="icon-parent">
                <i class="icon icon-twitter"><span>Twitter</span></i>
              </a>
              <a href="https://www.facebook.com/emikrause" class="icon-parent">
                <i class="icon icon-facebook"><span>Twitter</span></i>
              </a>
              <a href="https://www.linkedin.com/emikrause" class="icon-parent">
                <i class="icon icon-linkedin"><span>Twitter</span></i>
              </a>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {}
  },
  created: function () {
    console.log('hey')
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus" src="./home.styl">
