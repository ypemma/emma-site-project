<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="Who is Emma Ray?"
      subtitle=""
      image="/uploads/about-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>A Writer!</h3>
          <p>
            <strong>
              Emma is a research-driven journalist and photographer specializing in education and local governments.
            </strong>
          </p>
          <p>
            Much of Emma's work is currently under a different name, but in the future, you'll be able to find links to it here. 
            Highlights of her prior work has been syndicated in national papers through the Tribune News Network and USA Today Network.
          </p>

          <h3>A Photographer!</h3>
          <p>
            Emma is also a photographer, primarily to enhance coverage of her newswriting work. 
            You can find her on Twitter @YourPalEmma and on instagram in the future, where she uploads photos taken outside of work.
            She works in Orlando taking photos of models, products and street scenes.
          </p>
          <h3>A Learner??</h3>
          <p>
            Emma is currently learning how to make THIS WEBSITE (!?!?!) with some very cool and great help from <a href="https://odomojuli.com/">Juli Odomo</a>, who may end up reading this.
            
            lol
          </p>
        </div>

      
      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
